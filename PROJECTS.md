# Built with Kaazi Clips

Projects that use the Kaazi Clips local API.

Kaazi Clips runs on your own PC and exposes the same API its app uses. Anything
that can make an HTTP request can queue a video, follow its progress and read
the clips it made. Start with [docs/API.md](docs/API.md).

## Official

Built and maintained alongside Kaazi Clips.

- [Kaazi Clips OBS Plugin](https://github.com/kaazixd/clips-kitty-obs-plugin) - An OBS Studio dock that hands your stream to Kaazi Clips after it ends, and shows progress and time remaining. Nothing runs while you are live. (Windows, pre-release, needs the next Kaazi Clips release)

## Community

_Nothing listed yet. Built something? Add it here._

## Add your project

Open a pull request that adds one line under **Community**, in this format:

```md
- [Project name](https://link) - What it does, in one sentence. (Windows, macOS, Linux or web)
```

What gets listed:

- **It uses the documented API.** Build on the endpoints in
  [docs/API.md](docs/API.md), not by reading the database or the data folder
  directly, which change without notice.
- **The link works and says what the project is.** Open source is welcome but
  not required.
- **It is upfront about data.** If it sends anyone's videos, clips or accounts
  anywhere, it says so.

Add the `clips-kitty` topic to your repository too, so people can find it on
GitHub even before it is listed here.
