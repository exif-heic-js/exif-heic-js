# Exif-HEIC.js

A JavaScript library for reading [EXIF meta data](https://en.wikipedia.org/wiki/Exchangeable_image_file_format) from HEIC files created by iOS devices. It is derived from [Exif.js](https://github.com/exif-js/exif-js/blob/master/README.md).

The method `findEXIFinHEIC` takes an HEIC file in the form of `ArrayBuffer`, and return a collection of extracted EXIF tags. The method `findEXIFinJPEG` from Exif.js is also present to support JPEG files.
