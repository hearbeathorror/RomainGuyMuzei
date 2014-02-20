Romain Guy Muzei
================

An artwork source for Roman Nurik's [muzei](http://muzei.co) that displays random pictures from
Romain Guy's [Flickr photostream](http://www.flickr.com/photos/romainguy/).

Romain's photos are freely available for non-commercial projects (such as this one).

## What's there and what's coming

The app simply scraps the last 100 photos published on Romain's flickr account. It then picks
one at random and downloads it at the highest possible resolution (hmmm, pixels...).

These things are slated for later releases:
- Reduce the amount of requests to flickr by updating the photos list only once a day
- Download the whole photoset, not only the last 100 photos
- Add a settings screen (update interval, select album, whatever)

## Attributions
This app is based upon *Roman Nurik*'s *Muzei sample source app* and uses the Muzei API.
[Muzei](http://muzei.co) is released under the *Apache 2.0* license.

This app uses the *Retrofit* library from the fine guys over at *Square*.
[Retrofit](http://square.github.io/retrofit/) is released under the *Apache 2.0* license.

See the LICENSES file for further details.
You can find the integral text of the Apache 2.0 license here:
http://www.apache.org/licenses/LICENSE-2.0

The app icon was inspired by Eugenio Marletti (@Takhion).

## License
*Romain Guy Muzei* is released under the *Apache 2.0* license.

```
Copyright 2014 Frakbot (Sebastiano Poggi and Francesco Pontillo)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```