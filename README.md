# custom-video-player
This project demonstrates the implementation of a custom video player using HTML, CSS, and JavaScript. The video player includes features such as play/pause, stop, progress bar, and timestamp.

## Overview

The Custom Video Player project is a simple web-based video player that provides users with basic video controls and displays the current playback progress. This project is ideal for understanding how to create and manage custom video controls using vanilla JavaScript. The player fetches video resources, handles user interactions, and updates the UI dynamically.

## Features

- Play and pause the video
- Stop the video and reset it to the beginning
- Update the progress bar as the video plays
- Display the current timestamp of the video
- Click on the progress bar to seek to a specific time in the video

## Usage

- Click the play button to start the video.
- Click the pause button to pause the video.
- Click the stop button to stop the video and reset it to the beginning.
- Use the progress bar to seek to a specific time in the video.
- The timestamp next to the progress bar updates as the video plays.

## How It Works

1. **HTML Structure:**
   - The HTML file defines the structure of the video player, including the video element, control buttons, progress bar, and timestamp display.

2. **JavaScript:**
   - **`getElementById`**: Retrieves elements from the DOM.
   - **Event Listeners**: Attached to the video and control buttons to handle user interactions.
     - `click` event on the video element to toggle play/pause.
     - `click` event on the play button to toggle play/pause.
     - `click` event on the stop button to stop the video.
     - `timeupdate` event on the video element to update the progress bar and timestamp.
     - `change` event on the progress bar to seek to a specific time in the video.

   - **Functions**:
     - `toggleVideoStatus()`: Toggles between playing and pausing the video.
     - `updatePlayIcon()`: Updates the play/pause button icon based on the video's status.
     - `updateProgress()`: Updates the progress bar and timestamp as the video plays.
     - `setVideoProgress()`: Sets the video playback time based on the progress bar value.
     - `stopVideo()`: Stops the video and resets the playback time to the beginning.

3. **CSS:**
   - Styles for the video player, controls, and other elements are defined in the CSS files to ensure a consistent and visually appealing layout.

![custom video player](https://github.com/user-attachments/assets/067dbfe2-3add-4b74-bd41-402757333ea1)


