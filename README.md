# episodes

episodes is a simple repo that contains master playlist [m3u8][1] files for
[Pokémon TV][2] that have been corrected. Some of the [CDN][3] that host the
m3u8 files, notably [Limelight Networks][4], return text responses where the
content is truncated.

As the [HLS][5] component m3u8 playlist files follow a predictable pattern,
e.g. playlist-_[0-9a-f]{40}_.m3u8, the full urls can be rediscovered through
brute force enumeration of the remaining characters.

[DP006][6]

[DP007][7]

[DP028][8]

[DP029][9]

[DP037][10]

### [DP040][11] - Top-Down Training!

Original m3u8 file [1040---top-down-training-9f2e7bba9d5117e48a1fa33b1a2ab91a29042e17.m3u8][12]
is available [here][13]

Fixed m3u8 file [DP040.m3u8][14]

### [DP044][15] - Mass Hip-Po-Sis!

Original m3u8 file [1044---mass-hip-po-sis-357d8279753bc79f72ce551143542433549ffc94.m3u8][16]
is available [here][17]

Fixed m3u8 file [DP044.m3u8][18]

## Viewing

MP3 url streams can be tested using [this online tool][19]

## License

episodes is released under the [MIT license][20]

  [1]: https://en.wikipedia.org/wiki/M3U
  [2]: https://www.pokemon.com/uk/pokemon-episodes/
  [3]: https://en.wikipedia.org/wiki/Content_delivery_network
  [4]: https://www.limelight.com/
  [5]: https://en.wikipedia.org/wiki/HTTP_Live_Streaming
  [6]: https://github.com/pkmntv/episodes/tree/master/DP006
  [7]: https://github.com/pkmntv/episodes/tree/master/DP007
  [8]: https://github.com/pkmntv/episodes/tree/master/DP028
  [9]: https://github.com/pkmntv/episodes/tree/master/DP029
  [10]: https://github.com/pkmntv/episodes/tree/master/DP037
  [11]: https://bulbapedia.bulbagarden.net/wiki/DP040
  [12]: https://raw.githubusercontent.com/pkmntv/episodes/master/1040---top-down-training-9f2e7bba9d5117e48a1fa33b1a2ab91a29042e17.m3u8
  [13]: https://s2.content.video.llnw.net/smedia/4953336d7f544f678a12270b176ea386/Ud/U_sVvfDHuxlYLw-8HlrNVNlmAKXl_K77XwGk4R1kE/1040---top-down-training-9f2e7bba9d5117e48a1fa33b1a2ab91a29042e17.m3u8
  [14]: https://raw.githubusercontent.com/pkmntv/episodes/master/DP040.m3u8
  [15]: https://bulbapedia.bulbagarden.net/wiki/DP044
  [16]: https://raw.githubusercontent.com/pkmntv/episodes/master/1044---mass-hip-po-sis-357d8279753bc79f72ce551143542433549ffc94.m3u8
  [17]: https://s2.content.video.llnw.net/smedia/4953336d7f544f678a12270b176ea386/FK/N5gRNbKEC1pQvTT4n0VGCSvuaDAO8bmx8zxVo8nsY/1044---mass-hip-po-sis-357d8279753bc79f72ce551143542433549ffc94.m3u8
  [18]: https://raw.githubusercontent.com/pkmntv/episodes/master/DP044.m3u8
  [19]: http://player.streamingtvguides.com/
  [20]: https://opensource.org/licenses/MIT