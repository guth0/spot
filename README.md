# spot
A dbus obfuscation for simple command line spotify control written in Bash.

## Usage
This tool abstracts away all the messy syntax of the `dbus-send` command on Linux for Spotify.

This tool can get data from spotify like the artist, song title, ablum of the current song.
It can also send instrutions to spotify to skip, go back, play, and pause.

You can also get all metadata from Spotify from `spot metadata`.

More detailed instructions and other utilities can be found with `spot help` (or just look at the source code).

## Disclaimer
This only works on select Linux OS's (Namely, I wrote this for use on Arch).

This may not work with Spotify clients other than the basic one from Spotify themselves.
