# Video and Audio 

## These exercises cover various aspects of Video and Audio elements in HTML, including basic embedding, multiple sources, subtitles, custom controls, responsiveness elements integration. You should practice these to gain a solid understanding of multimedia in HTML.

## Exercise 1: Basic Audio Player
Create an HTML file with an audio player that meets the following requirements:

Use the `<audio>` tag to embed an audio file (e.g., music.mp3).

Add controls so the user can play, pause, and adjust volume.

Display a fallback message if the browser does not support the audio element.

Add the autoplay attribute (but note that many browsers block autoplay).

Use the loop attribute to make the audio replay when it ends. (You'll able to do this exercise after learning of JavaScript)

## Exercise 2: Multiple Audio Sources with Fallback
Create an HTML file with an audio player that supports multiple formats for better browser compatibility:

Use the `<audio>` tag with controls.

Inside `<audio>`, include two `<source>` tags:

One with an .mp3 file.

Another with an .ogg file.

Set the type attribute correctly for each source (e.g., audio/mp3, audio/ogg).

Provide a fallback text like "Your browser does not support the audio element."

## Exercise 3: Basic Video Player
Create an HTML file with a video player that meets the following requirements:

Use the `<video>` tag to embed a video file (e.g., movie.mp4).`

Add controls to allow play, pause, volume, and fullscreen options.

Set the video width to 600px and height to 400px.

Display a fallback message if the browser does not support the video element.

Use the poster attribute to show a preview image before the video plays.

## Exercise 4: Multiple Video Sources with Subtitles
Create an HTML file with a video player that supports multiple formats and subtitles:

Use the `<video>` tag with controls, width="600", and height="400".

Inside `<video>`, include two `<source>` tags:

One with a .mp4 file.

Another with a .webm file.

Add subtitles using the `<track>` tag:

Use a .vtt (WebVTT) file for captions.

Set kind="subtitles", srclang="en", and label="English".

Provide a fallback message.

## Exercise 5: Responsive Video with Aspect Ratio
### (You'll be able to do this exercise after watching the CSS Video No 8)
Make a video responsive while maintaining its aspect ratio:

Use the `<video>` tag with controls.

Wrap the video in a `<div>` with a class (e.g., video-container).

Use CSS to ensure the video scales with the screen width while keeping a 16:9 aspect ratio.

Set max-width: 100% and height: auto on the video.



