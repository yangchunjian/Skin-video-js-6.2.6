# video.js-6.2.6
New skin video-js-6.2.6
<img src="https://github.com/maluklo/video-js-6.2.6/blob/master/video-js-6.2.6.png">
### Quick Start

```html
<link href="video-js-6.2.6/video-js.css" rel="stylesheet">
<script src="video-js-6.2.6/video.js"></script>

<video id="player" 
class="video-js vjs-default-skin" 
controls preload="none" 
width="960" 
height="400" 
poster="video-js-6.2.6/oceans.png" 
data-setup="{}">
<source src="http://vjs.zencdn.net/v/oceans.mp4" type="video/mp4">
<source src="http://vjs.zencdn.net/v/oceans.webm" type="video/webm">
<source src="http://vjs.zencdn.net/v/oceans.ogv" type="video/ogg">
</video>
```
### Or

```html
<link href="video-js-6.2.6/video-js.css" rel="stylesheet">
<script src="video-js-6.2.6/video.js"></script>

<video id="player" class="video-js"></video>
<script>
var Player = videojs("player", { 
"controls": true, 
"autoplay": false, 
"preload": "auto" ,
"poster": "video-js-6.2.6/oceans.png",
"width": 960,
"height": 400,
sources: [
{ src: 'https://vjs.zencdn.net/v/oceans.mp4', type: 'video/mp4'},
{ src: 'https://vjs.zencdn.net/v/oceans.webm', type: 'video/webm'},
{ src: 'https://vjs.zencdn.net/v/oceans.ogv', type: 'video/ogg'}
],
});
</script>
```

