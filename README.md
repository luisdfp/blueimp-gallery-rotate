# blueimp Gallery

- [Description](#description)
- [Setup](#setup)
- [License](#license)

## Description
This is a plugin for [blueimp Gallery](https://github.com/blueimp/Gallery). It adds buttons to rotate the image clockwise and counter-clockwise in the bottom left corner of the screen.

## Setup

1. You must include [blueimp Gallery](https://github.com/blueimp/Gallery) as shown in the instructions.

2. Copy the **css**, **img** and **js** files provided by this plugin and add them to your folders.

3. Include the stylesheet:

```html
<link rel="stylesheet" href="css/blueimp-rotate.css">
```

4. Include the script:

```html
<script src="js/blueimp-rotate.js"></script>
```
5. Add the image rotation controls:

```html
<div id="blueimp-gallery" class="blueimp-gallery">
    <div class="slides"></div>
    <h3 class="title"></h3>
    <a class="prev">‹</a>
    <a class="next">›</a>
    <a class="close">×</a>
    <a class="play-pause"></a>
    <ol class="indicator"></ol>

    <!-- Image rotation controls -->
    <a class="rotate-right"></a>
    <a class="rotate-left"></a> 
</div>
```

## License
Released under the [MIT license](https://opensource.org/licenses/MIT).