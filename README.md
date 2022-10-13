# 💾 **Krypton** Sources E**X**tension

A bunch of common item source implementations.

- [**Support Server**](https://discord.gg/8R4d8RydT4)

## 📦 What's included?

The following sources are included:

- [**YouTube**](https://youtube.com) 
- [**SoundCloud**](https://soundcloud.com) 
- [**Bandcamp**](https://bandcamp.com)
- [**Vimeo**](https://vimeo.com)
- [**Get Yarn**](https://getyarn.io)
- [**Twitch**](https://twitch.tv)
- [**Spotify**](https://spotify.com)
- [**Deezer**](https://deezer.com)
- [**Apple Music**](https://music.apple.com)
- [**Tidal**](https://tidal.com)

<details>
  <summary>Target Matrix</summary>
  <br>
  
  Each platform supports their own set of kotlin multi-platform targets
  | Source Name  | JVM | Linux X64 | Limitations  |
  | :----------- | :-: | :-------: | :----------- |
  | YouTube      | ✅  | 👷        | HTML Parsing |
  | SoundCloud   | ✅  | 👷        | HTML Parsing |
  | Bandcamp     | ✅  | 👷        | HTML Parsing |
  | Vimeo        | ✅  | 👷        | HTML Parsing |
  | Twitch       | ✅  | ❌        | HTML Parsing |
  | Spotify*     | ✅  | ✅        | N/A          |
  | Deezer       | ✅  | ✅        | N/A          |
  | Apple Music* | ✅  | ✅        | N/A          |
  | Tidal*       | ✅  | ✅        | N/A          |

  - ✅ Implemented 
  - 👷🏽 In-development 
  - ❌ Not implemented  

  <sub>* These sources cannot be streamed from, causing mirroring to take place</sub>
</details>

---

[Dimensional Fun](https://dimensional.fun) &bull; Licensed under Apache 2.0

