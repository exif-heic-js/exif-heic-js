# Exif-HEIC.js

A JavaScript library for reading [EXIF meta data](https://en.wikipedia.org/wiki/Exchangeable_image_file_format) from HEIC files created by iOS devices. It is derived from [Exif.js](https://github.com/exif-js/exif-js/blob/master/README.md).

The method `findEXIFinHEIC` takes an HEIC file in the form of `ArrayBuffer`, and return a collection of extracted EXIF tags. The method `findEXIFinJPEG` from Exif.js is also present to support JPEG files.

## Install

You can install it through NPM:

```
npm install https://github.com/exif-heic-js/exif-heic-js --save
```

then reference your local file:

```html
<script src="vendors/exif-js/exif-js"></script>
```

You can also use a minified version hosted by jsDelivr:

```html
<script src="https://cdn.jsdelivr.net/gh/exif-heic-js/exif-heic-js/exif-heic.min.js"></script>
```

## Example

A live demo is available on the [GitHub Pages site](https://exif-heic-js.github.io/exif-heic-js/example/).