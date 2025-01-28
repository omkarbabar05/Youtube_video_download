# YouTube Video Downloader

This Python script allows you to download YouTube videos using the `yt-dlp` library. You can specify the resolution of the video or download the highest available resolution by default.

## Features

- Download YouTube videos in a specified resolution (e.g., 720p, 1080p).
- Automatically download the highest available resolution if no resolution is specified.
- Simple and easy-to-use command-line interface.

## Prerequisites

Before running the script, ensure you have the following installed:

- Python 3.x
- `yt-dlp` library

## Installation

1. **Install Python**: Make sure you have Python 3.x installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

2. **Install `yt-dlp`**: You can install the `yt-dlp` library using pip. Run the following command in your terminal or command prompt:

   ```bash
   pip install yt-dlp
   ```

## Usage

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Run the Script**:

   ```bash
   python download_video.py
   ```

3. **Enter YouTube URL and Resolution**:

   - When prompted, enter the YouTube video URL.
   - Optionally, specify the resolution (e.g., `720p`, `1080p`). If you leave it blank, the script will download the highest available resolution.

   Example:

   ```bash
   Enter YouTube URL: https://www.youtube.com/watch?v=example
   Enter resolution (e.g., 720p or leave blank for highest): 720p
   ```

4. **Download the Video**:

   The video will be downloaded to the current directory with the title of the video as the filename.

## Example

```bash
$ python download_video.py
Enter YouTube URL: https://www.youtube.com/watch?v=example
Enter resolution (e.g., 720p or leave blank for highest): 720p
Download completed!
```
