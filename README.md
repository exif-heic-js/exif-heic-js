# Exif-HEIC.js

A JavaScript library for reading [EXIF meta data](https://en.wikipedia.org/wiki/Exchangeable_image_file_format) from HEIC files created by iOS devices.

The primary method `getTags` takes an HEIC file in the form of `ArrayBuffer`, and return a collection of extracted EXIF tags.

Most of the meaningful code was based on [Exif.js](https://github.com/exif-js/exif-js/blob/master/README.md).
