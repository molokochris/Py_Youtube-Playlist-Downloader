# YouTube Playlist Downloader

## Overview

The YouTube Playlist Downloader is a command-line tool that allows users to download all videos from a YouTube playlist. The program also saves metadata for each video, such as the title, description, views, length, rating, author, and publish date.

The program creates a directory for the playlist and stores all downloaded videos and their respective metadata files in that directory.

## Features

- Downloads all videos from a specified YouTube playlist.
- Saves metadata for each video in a text file.
- Automatically creates a directory named after the playlist ID or the current timestamp if the ID is not available.
- Handles errors gracefully and provides informative messages to the user.

## Usage

### Prerequisites

- Make sure you have Python installed on your system.
- Install the required Python packages using the following command:
  ```bash
  pip install pytube colorama

#Running the Program
You can run the program by executing the provided executable file created with PyInstaller. Follow the steps below:

##1. Download the Executable

Download the executable file from the repository or wherever it is hosted.

##2. Open a Terminal or Command Prompt

Navigate to the directory where the executable file is located.

##3. Run the Executable

Execute the program by entering the following command:
./youtube_playlist_downloader

##4. Enter the Playlist URL

When prompted, enter the URL of the YouTube playlist you want to download.

###Example
$ ./youtube_playlist_downloader
Please enter the YouTube playlist URL: https://www.youtube.com/playlist?list=PLw-VjHDlEOgtEcnB7LzHjlLg1o8klXvVD
Directory 'PLw-VjHDlEOgtEcnB7LzHjlLg1o8klXvVD' created.
Downloading: Video 1 Title
Downloaded: Video 1 Title
Metadata saved for: Video 1 Title
Downloading: Video 2 Title
Downloaded: Video 2 Title
Metadata saved for: Video 2 Title
...
Task Completed!!!

#Error Handling
The program includes error handling for various scenarios, such as:

- Invalid playlist URL
- Issues during the download process
- General unexpected errors
If an error occurs, a message will be displayed in red, and the program will attempt to continue downloading the remaining videos.

#Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to create an issue or submit a pull request.

#License
This project is licensed under the MIT License. See the LICENSE file for details.

#Acknowledgements
- Colorama for colorful terminal text.


