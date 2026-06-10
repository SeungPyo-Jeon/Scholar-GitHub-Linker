# Privacy Policy

Effective date: June 9, 2026

Scholar GitHub Linker is a Chrome Extension that helps users save academic PDFs found through Google Scholar into a GitHub repository selected by the user, and reopen those PDFs from the browser.

## Data the Extension Handles

The extension handles the following data only to provide its user-facing features:

- GitHub OAuth device authorization status and GitHub access token.
- GitHub repository owner/name selected by the user.
- PDF URLs, paper titles, and generated GitHub file paths for uploaded papers.
- Cached paper index from the selected GitHub repository.
- User preferences such as upload URL priority, institution resolver prefix, and PDF view mode.
- Web page content from Google Scholar result pages only for detecting paper titles and candidate paper links.

## How Data Is Used

The data is used to:

- Authenticate the user with GitHub.
- List repositories available to the authenticated GitHub account.
- Download a user-selected paper PDF from its source website.
- Upload that PDF to the user's selected GitHub repository.
- Display upload/view/delete controls on Google Scholar result pages.
- Search and display cached PDFs from the selected repository.
- Open private GitHub PDFs in the browser with the user's GitHub authorization.

## Data Storage

- GitHub access tokens are stored in `chrome.storage.session`, which is intended for session-lifetime storage.
- Non-sensitive settings and local caches are stored in `chrome.storage.local`.
- The extension does not operate a developer-controlled backend server by default.

## Data Sharing

The extension does not sell user data.

The extension transmits data only to services needed for its core functionality:

- GitHub, for authentication, repository listing, file upload, file deletion, and private PDF retrieval.
- Google Scholar, when the user searches Scholar from the extension or opens Scholar pages.
- Publisher, library, or institution resolver websites selected by the user when downloading a paper PDF.

The extension does not transmit user data to an analytics provider or advertising network.

## Host Permissions

The extension requests fixed access to:

- `scholar.google.com`, to inject upload/view controls into Google Scholar pages.
- `api.github.com`, `github.com`, and `raw.githubusercontent.com`, to authenticate with GitHub and manage user-selected repository files.

For publisher or institution PDF URLs, the extension requests site access only when the user chooses to upload a paper from that site.

## Remote Code

The extension does not load or execute remotely hosted code.

## User Control

Users can:

- Logout from GitHub in the extension popup.
- Change the selected repository.
- Delete PDFs from the selected GitHub repository through the Cloud tab.
- Remove the extension from Chrome to delete extension-controlled local/session storage.

## Contact

For privacy questions, contact the extension developer through the support contact listed on the Chrome Web Store listing or the project repository.

