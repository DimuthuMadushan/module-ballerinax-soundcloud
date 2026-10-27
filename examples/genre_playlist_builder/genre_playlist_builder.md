# Genre playlist builder

This example searches SoundCloud for tracks of a genre, lists the matches and, when enabled, collects them into a new private playlist and reads the playlist's tracks back.

## Prerequisites

1. A SoundCloud access token from an application registered on [SoundCloud for Developers](https://soundcloud.com/you/apps).

2. Create a `Config.toml` file in the example directory with the following values.

```toml
accessToken = "<ACCESS_TOKEN>"
genre = "synthwave"
searchTerm = "night drive"
maxTracks = 5
createPlaylist = false
```

Set `createPlaylist = true` to create the playlist in your account.

## Run the example

```bash
bal run
```
