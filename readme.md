# Kemono File Ripper

A Tampermonkey/Violentmonkey userscript for downloading all images, GIFs, videos, and linked files (including ZIPs) from Kemono posts.

## Features

- **Batch Download:** Downloads all images, GIFs, videos, and attached files (ZIPs, etc.) from Kemono posts
- **File Picker Support:** Uses the browser's file picker if available for saving the zip.
- **Downloading:** Adds a "Download Media" button next to Favorite/Flag on post pages.
- **Folder Naming:** Zip file is named {post title} by {creator}.zip.
- **Individual File:** Naming: All files are saved after the post title followed by a number (order) to sort them.
- **Works on:** Both `kemono.party` and `kemono.cr` domains.

## Usage

1. Install [Tampermonkey](https://www.tampermonkey.net/) or [Violentmonkey](https://violentmonkey.github.io/) in your browser.
2. Add this userscript.
3. Visit any Kemono post page.
4. Click the **Download Media** button next to Favorite/Flag.
5. Wait for the progress bar to complete and save the zip file.

## Notes

- Large files may take longer to download and zip.
- All downloads are direct from Kemono servers.
- The script does not support chunked downloads or resume for very large files.

## License

GPL-3.0 https://www.gnu.org/licenses/gpl-3.0.txt
