# episodes

episodes is a simple repo that contains master playlist [m3u8][1] files for
[Pokémon TV][2] that have been corrected. Some of the [CDN][3] that host the
m3u8 files, notably [Limelight Networks][4], return text responses where the
content is truncated.

As the [HLS][5] component m3u8 playlist files follow a predictable pattern,
e.g. playlist-_[0-9a-f]{40}_.m3u8, the full urls can be rediscovered through
brute force enumeration of the remaining characters.

## Listing

[DP006][6]
[DP007][7]

### [DP028][8] - Drifloon On the Wind!

Original m3u8 file [1028---drifloon-on-the-wind-bcde3656216e52a000cded219576f4e094d1933c.m3u8][9]
is available [here][10]

Fixed m3u8 file [DP028.m3u8][11]

### [DP029][12] - The Champ Twins!

Original m3u8 file [1029---the-champ-twins-ca3ef4cb214b933b7b9270923e90ab7c0675e25c.m3u8][13]
is available [here][14]

Fixed m3u8 file [DP029.m3u8][15]

### [DP037][16] - The Grass Menagerie!

Original m3u8 file [1037---the-grass-menagerie-169ae88b5fd18da528a65a20965e34014560cc05.m3u8][17]
is available [here][18]

Fixed m3u8 file [DP037.m3u8][19]

### [DP040][20] - Top-Down Training!

Original m3u8 file [1040---top-down-training-9f2e7bba9d5117e48a1fa33b1a2ab91a29042e17.m3u8][21]
is available [here][22]

Fixed m3u8 file [DP040.m3u8][23]

### [DP044][24] - Mass Hip-Po-Sis!

Original m3u8 file [1044---mass-hip-po-sis-357d8279753bc79f72ce551143542433549ffc94.m3u8][25]
is available [here][26]

Fixed m3u8 file [DP044.m3u8][27]

## Viewing

MP3 url streams can be tested using [this online tool][28]

## License

episodes is released under the [MIT license][29]

  [1]: https://en.wikipedia.org/wiki/M3U
  [2]: https://www.pokemon.com/uk/pokemon-episodes/
  [3]: https://en.wikipedia.org/wiki/Content_delivery_network
  [4]: https://www.limelight.com/
  [5]: https://en.wikipedia.org/wiki/HTTP_Live_Streaming
  [6]: https://github.com/pkmntv/episodes/tree/master/DP006
  [7]: https://github.com/pkmntv/episodes/tree/master/DP007    
  [8]: https://bulbapedia.bulbagarden.net/wiki/DP028
  [9]: https://raw.githubusercontent.com/pkmntv/episodes/master/1028---drifloon-on-the-wind-bcde3656216e52a000cded219576f4e094d1933c.m3u8
  [10]: https://s2.content.video.llnw.net/smedia/4953336d7f544f678a12270b176ea386/ZG/gEZeJ5OWBPq7tCIrkDc6lp_sIe54qJMVyOEPoAWcA/1028---drifloon-on-the-wind-bcde3656216e52a000cded219576f4e094d1933c.m3u8
  [11]: https://raw.githubusercontent.com/pkmntv/episodes/master/DP028.m3u8
  [12]: https://bulbapedia.bulbagarden.net/wiki/DP029
  [13]: https://raw.githubusercontent.com/pkmntv/episodes/master/1029---the-champ-twins-ca3ef4cb214b933b7b9270923e90ab7c0675e25c.m3u8
  [14]: https://s2.content.video.llnw.net/smedia/4953336d7f544f678a12270b176ea386/8Z/WeNEiO1TgFK4kxhg6db5eB0l3Qg5guDyeFabRd3v0/1029---the-champ-twins-ca3ef4cb214b933b7b9270923e90ab7c0675e25c.m3u8
  [15]: https://raw.githubusercontent.com/pkmntv/episodes/master/DP029.m3u8
  [16]: https://bulbapedia.bulbagarden.net/wiki/DP037
  [17]: https://raw.githubusercontent.com/pkmntv/episodes/master/1037---the-grass-menagerie-169ae88b5fd18da528a65a20965e34014560cc05.m3u8
  [18]: https://s2.content.video.llnw.net/smedia/4953336d7f544f678a12270b176ea386/YX/8JK-bUki9ikTGiusm6SWFIVSrdlm9N30JDiS5O9FU/1037---the-grass-menagerie-169ae88b5fd18da528a65a20965e34014560cc05.m3u8
  [19]: https://raw.githubusercontent.com/pkmntv/episodes/master/DP037.m3u8
  [20]: https://bulbapedia.bulbagarden.net/wiki/DP040
  [21]: https://raw.githubusercontent.com/pkmntv/episodes/master/1040---top-down-training-9f2e7bba9d5117e48a1fa33b1a2ab91a29042e17.m3u8
  [22]: https://s2.content.video.llnw.net/smedia/4953336d7f544f678a12270b176ea386/Ud/U_sVvfDHuxlYLw-8HlrNVNlmAKXl_K77XwGk4R1kE/1040---top-down-training-9f2e7bba9d5117e48a1fa33b1a2ab91a29042e17.m3u8
  [23]: https://raw.githubusercontent.com/pkmntv/episodes/master/DP040.m3u8
  [24]: https://bulbapedia.bulbagarden.net/wiki/DP044
  [25]: https://raw.githubusercontent.com/pkmntv/episodes/master/1044---mass-hip-po-sis-357d8279753bc79f72ce551143542433549ffc94.m3u8
  [26]: https://s2.content.video.llnw.net/smedia/4953336d7f544f678a12270b176ea386/FK/N5gRNbKEC1pQvTT4n0VGCSvuaDAO8bmx8zxVo8nsY/1044---mass-hip-po-sis-357d8279753bc79f72ce551143542433549ffc94.m3u8
  [27]: https://raw.githubusercontent.com/pkmntv/episodes/master/DP044.m3u8
  [28]: http://player.streamingtvguides.com/
  [29]: https://opensource.org/licenses/MIT