# YouTube Video Downloader with GUI

This Python script allows you to download YouTube videos with a simple graphical user interface (GUI) using the `yt-dlp` library. The app lets you choose the desired video quality, shows a progress bar, and keeps the interface responsive by running the download in a separate thread.

## Features:

- Input YouTube video URL.
- Select video quality (best, worst, 1080p, 720p, 480p, 360p).
- Shows download progress using a progress bar.
- Runs download in a separate thread to keep the GUI responsive.

## Prerequisites:

Make sure you have the following installed:

- Python 3.x
- `yt-dlp` library for downloading videos.
- `tkinter` for the GUI (should be installed by default with Python).

## Installation:

1. **Clone or Download the Repository:**

   Download or clone this repository to your local machine.

2. **Install Dependencies:**

   Open a terminal/command prompt and run the following command to install `yt-dlp`:

   ```
   pip install yt-dlp
   ```

   tkinter should already be installed with Python.

## Usage:

Run the Jupyter Notebook:

```
Interface:

URL Input: Enter the YouTube video URL you want to download.

Quality Selection: Choose the quality (e.g., best, 1080p, 720p).

Progress Bar: The progress bar will update as the video downloads.

Start the Download: Click the "Download" button to begin the download. The download process will run in a separate thread to prevent the interface from freezing.

Download Completion: Once the download is complete, you’ll see a success message.
```

## License:

This project is open-source, feel free to modify or distribute it as you see fit.
