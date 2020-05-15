# fotorama-mcsms
Modifying version of fotorama carousel, HTML5 video player included.

## Usage

### Initializing
Place this link tag somewhere on the head tag.
```HTML
<link rel="stylesheet" type="text/css" href="https://raw.githubusercontent.com/megacarlossm/fotorama-mcsms/master/fotorama-mcsm.min.css" />
```
Place this script in the end of body tag.
```HTML
<script type="text/javascript" src="https://raw.githubusercontent.com/megacarlossm/fotorama-mcsms/master/fotorama-mcsm.min.js"></script>
```

### HTML
```HTML
<div class="fotorama" data-width="100%" data-maxheight="500px" data-nav="thumbs">
	<a data-thumb="VideoThumbRoute" href="VideoRoute" data-type="video/mp4"></a>
	<a data-thumb="VideoThumbRoute2" href="VideoRoute2" data-type="video/mp4"></a>
</div>
```

### JS
```JS
$(".fotorama").fotorama();
```

Thats all what you have to do. This project only works with MP4 for now.
