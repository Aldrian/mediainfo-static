#mediainfo-static
====

Static binaries for `mediainfo`.

Based on <https://github.com/eugeneware/ffmpeg-static>.

Binaries are from <https://mediaarea.net/fr/MediaInfo/Download>

Usage
----

```js
var mediainfo = require('mediainfo-static');
console.log(mediainfo.path);
```

Version Notes
----

Currently supports Mac OS X (64-bit), Linux (32 and 64-bit) and Windows
(32 and 64-bit).

Currently version `18.12` is installed for Mac, Windows and Linux.

I pulled the versions from the MediaInfo download pages linked from the
official MediaInfo site. Namely:

* [OSX](https://mediaarea.net/fr/MediaInfo/Download/Mac_OS)
* [Linux](https://mediaarea.net/fr/MediaInfo/Download/Ubuntu)
* [Windows](https://mediaarea.net/fr/MediaInfo/Download/Windows)

Acknowledgements
----

Special thanks to [eugeneware](https://github.com/eugeneware) for <https://github.com/eugeneware/ffmpeg-static>, which this is based upon.
