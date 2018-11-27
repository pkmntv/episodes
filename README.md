# episodes

episodes is a simple repo that contains master playlist [m3u8][1] files for
[Pokémon TV][2] that have been corrected. Some of the [CDN][3] that host the
m3u8 files, notably [Limelight Networks][4], return text responses where the
content is truncated.

As the [HLS][5] component m3u8 playlist files follow a predictable pattern,
e.g. playlist-_[0-9a-f]{40}_.m3u8, the full urls can been rediscovered through
brute force enumeration of the remaining characters.

## Listing

### DP006 - Different Strokes for Different Blokes

Original m3u8 file [1006---different-strokes-b7dd95a50aa8ffe3db327334d390633818e4f711.m3u8][6]
is available [here][7]

Fixed m3u8 file [DP006.m3u8][8]

## License

episodes is released under the [MIT license][9]

  [1]: https://en.wikipedia.org/wiki/M3U
  [2]: https://www.pokemon.com/uk/pokemon-episodes/
  [3]: https://en.wikipedia.org/wiki/Content_delivery_network
  [4]: https://www.limelight.com/
  [5]: https://en.wikipedia.org/wiki/HTTP_Live_Streaming
  [6]: https://raw.githubusercontent.com/pkmntv/episodes/master/1006---different-strokes-b7dd95a50aa8ffe3db327334d390633818e4f711.m3u8
  [7]: https://s2.content.video.llnw.net/smedia/4953336d7f544f678a12270b176ea386/sX/V6EbWaIzIxKCl8tpDWgcRred5T61FLqJmJZS7_7n0/1006---different-strokes-b7dd95a50aa8ffe3db327334d390633818e4f711.m3u8
  [8]: https://raw.githubusercontent.com/pkmntv/episodes/master/DP006.m3u8
  [9]: https://opensource.org/licenses/MIT