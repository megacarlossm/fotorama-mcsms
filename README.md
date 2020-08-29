# fotorama-mcsms
Modifying version of fotorama carousel, HTML5 MP4 video player included.

## Usage

### Initializing
Place this link tag somewhere on the head tag.
```HTML
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/megacarlossm/fotorama-mcsms/fotorama-mcsm.min.css" />
```
Place this script in the end of body tag.
```HTML
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/megacarlossm/fotorama-mcsms/fotorama-mcsm.min.js"></script>
```

### HTML
```HTML
<div class="fotorama" data-width="100%" data-maxheight="500px" data-nav="thumbs">
    <a data-thumb="https://us.123rf.com/450wm/tihiychelovek/tihiychelovek1907/tihiychelovek190700099/130611355-cobweb-on-a-dark-background-dark-background.jpg?ver=6" href="http://techslides.com/demos/sample-videos/small.mp4" data-type="video/mp4"></a>    
    <a data-thumb="https://i.pinimg.com/564x/1c/bb/66/1cbb664a37bcb91ecbe40fae5ec07e11.jpg" href="https://www.prontus.cl/prontusPlayer4/samples/video/PIPER_SHORT_FILM_720p.mp4" data-type="video/mp4"></a>    
</div>
```

### JS
```JS
$(".fotorama").fotorama();
```

Thats all what you have to do. This project only works with MP4 for now, and needs Jquery.
