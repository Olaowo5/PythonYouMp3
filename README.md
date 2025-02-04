# YouTube to MP3 Converter

This Python script allows you to download audio from YouTube videos and convert it to MP3 format. 
## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x installed on your system. You can download it from [python.org](https://www.python.org/downloads/).
- `yt-dlp` library: You can install this using pip. See setup instructions below.
- `ffmpeg` executable available in your system path. This is essential for audio conversion.

## Setup Instructions

1. **Clone the Repository** (if applicable) or download the script directly.

2. **Install Required Libraries**:

    Open a terminal or command prompt and execute:
    ```bash
    pip install yt-dlp
    ```

3. **FFmpeg Installation**:

   - Download a static build of FFmpeg from the [official website](https://ffmpeg.org/download.html).
   - Extract it to a directory (e.g., `C:\ffmpeg` for Windows users).
   - Add the execution to the path directory.
   - Link for instructions [youtube Guide](https://www.youtube.com/watch?v=JR36oH35Fgg).

4. **Script Configuration**:

   - Open the script in your preferred text editor or IDE (such as Visual Studio Code).
   - Update the `ffmpeg_path` variable with the correct path to your FFmpeg installation, ensuring it points to the `bin` directory.

## Usage

1. **Run the Script**:

    Execute the script using Python:

    ```bash
    python path/to/your/main.py
    ```

    Replace `path/to/your/main.py` with the actual path to where your Python script is located.

    or Your perosnal IDE

2. **Follow the Prompts**:

    - Enter the YouTube video URL you want to download.
    - Specify the download directory for the MP3 file. Defaults to `downloads` if not specified.

## How It Works

- The script uses `yt-dlp` to fetch and process the YouTube video, and `ffmpeg` to convert the audio to MP3 format.
- Upon execution, the script will download the highest quality audio track available, converting it to MP3 in the specified directory.

## Notes

- Ensure that the provided YouTube URLs are accessible and authorized for downloading.
- Use this tool responsibly and adhere to YouTube's terms of service.
