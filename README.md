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

[DP040][11]

[DP044][12]

## Viewing

MP3 url streams can be tested using [this online tool][13]

## License

episodes is released under the [MIT license][14]

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
  [11]: https://github.com/pkmntv/episodes/tree/master/DP040
  [12]: https://github.com/pkmntv/episodes/tree/master/DP044
  [13]: http://player.streamingtvguides.com/
  [14]: https://opensource.org/licenses/MIT