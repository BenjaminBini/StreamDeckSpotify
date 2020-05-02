# Spotify Plugin for StreamDeck

## Usage

You can download the plugin from the [release page]().

This plugins shows the artwork of the song currently playing and allows you to play/pause by pressing your StreamDeck button.

When you activate the plugin on your StreamDeck (by placing its action on one button), it will redirect you to Spotify website to authorize the application to connect to your Spotify account to see and control what's playing.

## Development

To install from source, you will need to rename the file called `.env.sample` at the root of the project to `.env` and set the values from a valid Spotify Application created on your [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/applications).

Then build your application, build it with Visual Studio using Release Mode and run this command from the command line from the root of the project:

```sh
$ ./install.bat RELEASE com.bini.spotify
```