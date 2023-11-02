# A :fullscreen pseudo class demo without JavaScript

The `:fullscreen` element works with element turned fullscreen by the [Fullscreen API][fullscreen-api]. You can
trigger Fullscreen API by [HTMLElement.requestFullscreen()][requestfullscreen], but that is not the only way.

[video][video-element], and potential other elements in the future, uses Fullscreen API in their native controls
without any JavaScript. This [simple demo page][demo] is to demonstrate it.

[fullscreen-api]: https://developer.mozilla.org/en-US/docs/Web/API/Fullscreen_API
[requestfullscreen]: https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/requestFullscreen
[video-element]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video
[demo]: index.html


## License

* The [demo file][demo] source code is licensed under the MIT License. You may find a copy [here][mit-license].
* The video file [rotating-cube.webm][video-file] is published under the public domain.

[video-file]: assets/rotating-cube.webm
[mit-license]: LICENSE