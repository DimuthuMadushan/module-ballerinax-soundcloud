# Track engagement workflow

This example reads a track, lists the users who liked it and the comments on it, and, when enabled, likes the track and posts a comment.

## Prerequisites

1. A SoundCloud access token from an application registered on [SoundCloud for Developers](https://soundcloud.com/you/apps).

2. Create a `Config.toml` file in the example directory with the following values.

```toml
accessToken = "<ACCESS_TOKEN>"
trackUrn = "<TRACK_URN>"
commentText = "Great track!"
engage = false
```

Set `engage = true` to like the track and post the comment.

## Run the example

```bash
bal run
```
