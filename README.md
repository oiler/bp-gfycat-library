# README.md

## Authorship
Original version of this library was authored by Nick Wheatley-Schaller, while at Baseball Prospectus. In summer of 2016, in the middle of website redesign, BP has extended the functionality of this library to work with other media formats.

## Usage
Original usage (gfycat only) was as follows:
```
<div class="gfyitem" data-autoplay="false" data-controls="false" data-expand="false" data-id="RingedSereneHypacrosaurus" data-title="true"></div>
```
From the original docs:
> data-autoplay: if false, video will have to be clicked on/moused over to play. If not, the video will autoplay. Don't use this with the gyfcat_hover script.

> data-controls: this determines if the playback controls appear. Leave false for gfycat_hover, true for gfycat_test

> data-id: Important! This will be the id in the url of the gfycat you uploaded. For example, this particular gfycat was http://gfycat.com/RingedSereneHypacrosaurus

## Version 1.1
Before embarking on the fork of this library, we added in the functionality Nick had in the "test" file to allow for the gif to be played by mouseOver or click - as determined by an additional (and optional) data attribute. Default value is set to use mouseOver.

So update usage is as follows:
```
<div class="gfyitem" data-mouseOver="true" data-autoplay="false" data-controls="false" data-expand="false" data-id="RingedSereneHypacrosaurus" data-title="true"></div>
```

This functionality is available in the [1.1 version](https://github.com/oiler/bp-gfycat-library/tree/master/v1.1) of gfycat.js.

## Example
See example.html for basic usage.