# GooglePhotosDownloader
Google Photos used to have seamless integration with Google Drive, allowing users to access their photos directly from their file system. However, Google removed this feature, forcing users to manually download their photos via the Google Photos web interface.Many users, including myself, prefer to store their Google Photos locally on a NAS for backup and easy access. This script automates the entire process with just one click.

✅ Easy Selection: Choose the year and month via a modern Windows 11 UI
✅ Automated Download: Downloads all photos for the selected period directly to a local folder
✅ Google Photos API Integration: Uses rclone to fetch media efficiently
✅ Progress Indicator: Live progress bar, file count, and speed while downloading
✅ Smart Setup:
Installs rclone automatically if not present
Sets up Google Photos API if not configured
✅ Bandwidth Limiting (Optional): Prevents hitting Google API quotas
✅ Works on Windows & Synology NAS (via Docker or SSH)
📖 Background (English)
Google's decision to remove Photos integration from Drive left many users struggling to manage their cloud-stored images efficiently. Instead of relying on the slow manual download process, this script provides an automated solution that keeps your local storage in sync with your cloud photos.
