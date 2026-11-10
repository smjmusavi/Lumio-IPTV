# Lumio IPTV for older Samsung TVs

An IPTV player designed specifically for older Samsung Smart TVs from 2016 onward, running Tizen 2.4 or newer.

Lumio IPTV brings live television, programme guides, movies and series to your Samsung TV using your own compatible playlists. Its interface is designed for navigation with a standard TV remote, with particular attention to compatibility with older Tizen televisions.

## Compatibility

- Samsung Smart TVs from 2016 onward (Older devices are not tested but might work.).
- Tizen 2.4 or newer.
- Navigation using a Samsung TV remote.

This is the application's intended compatibility range. Actual performance and playback support depend on the TV model, firmware, stream format and provider. Not every model within this range has been individually tested.

## Features

- Live TV in List, Grid and Cards views.
- Channel groups, search, favourites and recently watched channels.
- Electronic programme guide support.
- Multiple saved playlists.
- Movies and series browsing.
- Saved playback progress for on-demand content.
- Configurable interface and playback settings.

## Playback Controls, Multiple Sources & EPG Timeline

- **Playback arrow shortcuts:** During live playback, press **Up** for the information bar, **Down** for playback controls, **Left** for the channel list, and **Right** for programme details.

- **Multiple sources and quality selection:** Keep alternative streams together under one channel instead of showing each as a separate channel.

  To use source grouping, first organise your playlist using an online playlist editor such as **[m3u4u.com](https://m3u4u.com/)**. Put the alternative streams in the **same group**, give them the **same base channel name**, and use recognised suffixes—for example:

  | Playlist entry | Stream URL |
  |---|---|
  | `Example TV` | Main stream |
  | `Example TV HD` | Alternative HD stream |
  | `Example TV FHD` | Alternative Full HD stream |
  | `Example TV SD` | Alternative SD stream |
  | `Example TV +1` | One-hour-delayed stream |
  | `Example TV PS` | Public stream |
  | `Example TV PS1` | Another public stream |

  Each entry should contain its corresponding stream URL. Keep the base name identical and use each suffix only once within that group.

  Save your changes, obtain the **edited playlist’s output URL**, and add that link to Lumio IPTV. The app combines these entries into a single **Example TV** channel. During playback, open **Channel sources** to choose an alternative stream.

  **Video quality selection is separate:** supported adaptive HLS links expose multiple resolutions within one stream. For those links, choose **Auto** or an available fixed quality. Lumio can remember your source and quality choices.

- **EPG timeline:** Browse programme schedules across channels, view descriptions and broadcast times, and explore earlier and upcoming programmes.

## Download

Open the Releases section of this repository and download the latest Lumio IPTV `.wgt` file.

## Install using Apps2Samsung

1. Install Apps2Samsung on your computer or supported phone.
2. Follow its instructions to enable Developer Mode on your Samsung TV.
3. Connect Apps2Samsung to the TV.
4. Choose the custom WGT installation option.
5. Select the downloaded Lumio IPTV `.wgt` file.
6. Follow the signing and installation instructions.
7. Open Lumio IPTV on your TV and add your playlist.

Apps2Samsung: https://apps2samsung.com/

## Playlists and content

Lumio IPTV is a player. No channels, subscriptions or playlist credentials are included.

You must supply your own compatible playlist and have permission to access its content.

## Reporting problems

Please open an issue in this repository and include:

- Your Samsung TV model.
- Your Tizen version, if known.
- Your Lumio IPTV version.
- A description of the problem and the steps that cause it.

Do not post playlist passwords, subscription credentials or private playlist links.
