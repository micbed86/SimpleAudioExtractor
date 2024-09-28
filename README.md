# SimpleAudioExtractor

SimpleAudioExtractor is a user-friendly application that allows you to extract audio tracks from video files and save them as MP3 files.

## Features

- Extract audio from various video formats (MP4, AVI, MOV, MKV)
- Save extracted audio as MP3
- Adjustable audio bitrate (32-320 kbps)
- Estimated output file size calculation
- Simple and intuitive graphical user interface
- Dark mode interface with gradient background

## Requirements

- Windows 10 or later
- FFmpeg (automatically included in the .exe release version, which is why the .exe file is so big)

## Installation

### Option 1: Using the pre-compiled executable (Windows only)

1. Go to the [Releases](https://github.com/micbed86/SimpleAudioExtractor/releases) page
2. Download the latest `SimpleAudioExtractor.exe` file
3. Run the executable

### Option 2: Running from source

1. Ensure you have Python 3.7 or later installed
2. Clone this repository:
```git clone https://github.com/micbed86/SimpleAudioExtractor.git```
3. Install the required dependencies:
```pip install customtkinter Pillow```
4. Install FFmpeg and make sure it's available in your system PATH
5. Run the script:
```python SimpleAudioExtractor.py```


## Usage

1. Launch the application
   - optionally select preferred language
2. Click "Select File" to choose a video file
3. Select an output folder (if empty, the source file folder will be used for output)
4. Adjust the compression level if needed by adjusting the audio bitrate/quality (by default, the original bitrate will be used - no compression).
5. Click "Start" to begin the extraction process
6. Access your extracted audio file by clicking on the 'Open folder' or 'Open file' button, which appears below the progress bar, once the process is completed

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check the [issues page](https://github.com/micbed86/SimpleAudioExtractor/issues) if you want to contribute.

## License

This project is licensed under the MIT License.

## Acknowledgments

- This project uses [FFmpeg](https://ffmpeg.org/) for audio extraction
- UI built with [CustomTkinter](https://github.com/TomSchimansky/CustomTkinter)

## Author

micbed86 - [GitHub Profile](https://github.com/micbed86)

## Version

Current version: see [Releases](https://github.com/micbed86/SimpleAudioExtractor/releases)


