# episodes

episodes is a simple repo that contains master playlist [m3u8][1] files for
[Pokémon TV][2] that have been corrected. Some of the [CDN][3] that host the
m3u8 files, notably [Limelight Networks][4], return text responses where the
content is truncated.

As the [HLS][5] component m3u8 playlist files follow a predictable pattern,
e.g. playlist-_[0-9a-f]{40}_.m3u8, the full urls can been rediscovered through
brute force enumeration of the remaining characters.

## Listing

### DP006 - [Different Strokes for Different Blokes][6]

Original m3u8 file [1006---different-strokes-b7dd95a50aa8ffe3db327334d390633818e4f711.m3u8][7]
is available [here][8]

Fixed m3u8 file [DP006.m3u8][9]

### DP007 - Like It or Lup It!

Original m3u8 file [1007---like-it-or-lup-it-4472400aa90a131db29f9b0b4f238fe8c5db0096.m3u8][10]
is available [here][11]

Fixed m3u8 file [DP007.m3u8][12]

## Viewing

MP3 url streams can be tested using [this online tool][13]

## License

episodes is released under the [MIT license][14]

  [1]: https://en.wikipedia.org/wiki/M3U
  [2]: https://www.pokemon.com/uk/pokemon-episodes/
  [3]: https://en.wikipedia.org/wiki/Content_delivery_network
  [4]: https://www.limelight.com/
  [5]: https://en.wikipedia.org/wiki/HTTP_Live_Streaming
  [6]: https://bulbapedia.bulbagarden.net/wiki/DP006
  [7]: https://raw.githubusercontent.com/pkmntv/episodes/master/1006---different-strokes-b7dd95a50aa8ffe3db327334d390633818e4f711.m3u8
  [8]: https://s2.content.video.llnw.net/smedia/4953336d7f544f678a12270b176ea386/sX/V6EbWaIzIxKCl8tpDWgcRred5T61FLqJmJZS7_7n0/1006---different-strokes-b7dd95a50aa8ffe3db327334d390633818e4f711.m3u8
  [9]: https://raw.githubusercontent.com/pkmntv/episodes/master/DP006.m3u8
  [10]: https://raw.githubusercontent.com/pkmntv/episodes/master/1007---like-it-or-lup-it-4472400aa90a131db29f9b0b4f238fe8c5db0096.m3u8
  [11]: https://s2.content.video.llnw.net/smedia/4953336d7f544f678a12270b176ea386/uE/P-JUoMCtUH6Lqtd5wTsbojS8j3pyRgdvrWXTxj5s8/1007---like-it-or-lup-it-4472400aa90a131db29f9b0b4f238fe8c5db0096.m3u8
  [12]: https://raw.githubusercontent.com/pkmntv/episodes/master/DP007.m3u8
  [13]: http://player.streamingtvguides.com/
  [14]: https://opensource.org/licenses/MIT