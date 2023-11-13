# Merged Video Playback Readme

## Introduction
This HTML file provides a simple web page for playing two video files consecutively using the Video.js library. The videos are merged into a single player, and when the first video ends, the second video automatically starts playing.

## Getting Started
To use this code, follow these steps:

1. Clone the repository or download the HTML file.

   ```bash
   git clone https://github.com/your/repository.git
   ```

2. Open the HTML file (`index.html`) in a web browser.

## Dependencies
- [Video.js](https://videojs.com/): A JavaScript and CSS library that makes it easy to work with HTML5 video.

## Usage
- The two video files (`file1.mp4` and `file2.mp4`) are specified as the video sources within the `<video>` tag.
  
   ```html
   <video id="mergedVideo" class="video-js vjs-default-skin" controls preload="auto" width="640" height="360">
       <source src="file1.mp4" type="video/mp4" />
       <source src="file2.mp4" type="video/mp4" />
   </video>
   ```

- The script in the `<script>` tag controls the video playback. It uses Video.js to create a player, switches to the next video when the current one ends, and sets up autoplay for the first video.

   ```javascript
   // JavaScript code for video playback and switching
   // ...
   ```

## Customization
- You can customize the appearance of the video player by modifying the CSS styles in the `<style>` tag.
  
   ```css
   body {
       font-family: 'Arial', sans-serif;
       background-color: #f2f2f2;
       margin: 0;
       padding: 0;
       display: flex;
       justify-content: center;
       align-items: center;
       height: 100vh;
   }

   #mergedVideo {
       border-radius: 8px;
       box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
   }
   ```

## License
This code is provided under the [MIT License](LICENSE).

Feel free to reach out if you have any questions or suggestions!