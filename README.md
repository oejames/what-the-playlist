## Purpose of This Fork
The original site does not use an internal database - this fork modifies the backend by loading a database for each user once at the beginning of a session and then pulling from that database for later data retrieval. This is designed to replace the current live search functionality, which can be slow/resource-intensive.
# what the playlist

Ever hear a song for the first time in years and remember that one playlist you made 4 years ago but think to yourself _what the #$!% was the name of that playlist?_.

what the playlist looks through your created and followed playlists to find the one with that song/album/artist you just can't get out of your head.<br><br>

## Setup

Make sure to install the dependencies:

```bash
yarn install
```

## Development Server

Start the development server on http://localhost:3000

```bash
yarn dev
```

## Production

Build the application for production:

```bash
yarn build
```

Locally preview production build:

```bash
yarn preview
```
## Acknowledgments
This is a fork of the original What The Playlist by @haykkh. Many thanks to the original author for the inspiration and groundwork laid out in Issue #54.
