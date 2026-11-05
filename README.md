# Fabulous 55 💜🎰
A responsive, self-playing Vegas-and-arcade birthday show for Mom's 55th!

## Run it
Enable **Settings → Pages → Deploy from a branch → main → /(root)**, then visit https://brazygryl-cell.github.io/fabulous-55/.

On a TV, use a browser or cast your phone/computer screen. Tap **Start the Show** once to enable media playback with sound. After that the show advances and loops automatically.

## Add pictures and family messages
Edit the two arrays near the top of the JavaScript in `index.html`:
```js
const PHOTOS = ['assets/photos/mom-01.jpg'];
const FAMILY_VIDEOS = [
  {name:'From Auntie', src:'assets/videos/auntie.mp4'},
  {name:'From the Grandkids', src:'assets/videos/grandkids.mp4'}
];
```
Create those folders and upload matching photo/video files. MP4 (H.264/AAC) is a good format for video compatibility.

**Privacy reminder:** This repository is PUBLIC. Any photos and videos committed here can be accessed by others. Get permission from family members before uploading personal videos. Large or private media may be better hosted separately.

## Controls
Pause / resume, previous / next, sound, fullscreen. Arrow keys navigate and the spacebar pauses. Layout adapts to mobile and wide-screen TV.

## Coming next
Photos, real birthday messages, custom Vegas visuals, video transitions, music, and more personalized scenes.
