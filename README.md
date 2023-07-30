# Torrent to Google Drive Downloader and Converter

This Colab Notebook allows you to download your favorite videos from torrents directly in Google Colab, convert them to MP4 format, and save them to your Google Drive. This is especially helpful for playing videos on older TVs that only support the MP4 format. Simply download your neatly processed output MP4 file from Google Drive onto a pendrive and watch it on your TV.

## Features

- Download videos from torrents using magnet links in Google Colab.
- Convert video files (.mkv, .avi, .mov) to MP4 format compatible with most devices.
- Uses a GPU instance of Google Colab
- Save the converted files directly to your Google Drive for easy access and sharing.

## How to Use

1. Import the NoteBook into your Google Colab
2. When prompted, enter the magnet link of the torrent you want to download.
3. The script will download the torrent into a temporary directory in the Colab environment.
4. Any video files in the torrent are then converted to MP4 format.
5. The converted files are saved to your Google Drive. From there, you can download your MP4 file, put it on a pendrive, and watch it on your TV.

## Limitations

- Depending on the size of the torrent and the load on the Colab server, the download and conversion process can be slow.

## Acknowledgements

This script uses the [libtorrent](https://www.libtorrent.org/) library for torrent downloading and [FFmpeg](https://ffmpeg.org/) for video file conversion.
