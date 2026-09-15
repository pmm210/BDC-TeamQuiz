# BDC Team Quiz Challenge

Static website for GitHub Pages. No server or build is required.

## Publish

Upload the contents of this folder (including vendor/) to the root of your GitHub repository. In Settings > Pages, choose Deploy from a branch, main, and / (root), then Save.

## Data

Uploaded spreadsheets are read in the browser and are not sent to GitHub. Session data is stored in that browser. Passwords remain in memory. The website does not synchronize sessions between devices or browsers.

To move an existing localhost session: download its session backup, open the published website, and use Restore session. Localhost storage does not automatically transfer to the published address. Do not commit session backups or student spreadsheets to the repository.

Student marks remain visible to the host in the import screen but are hidden in team cards and team exports. This is a host-operated webpage, not an authenticated student portal.

Bundled Excel reader: SheetJS CE 0.20.3 (Apache-2.0).
