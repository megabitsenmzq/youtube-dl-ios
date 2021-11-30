# youtube-dl-ios (Megabits fork)

> [youtube-dl][youtube-dl] for iOS, with [Pythonista][pythonista]

Download a video (or its audio track) by copy the URl to Pythonista.

This script passes the
URL to youtube-dl to do the actual download. After the download completes, the
file is opened in a QuickLook window where it may be saved to camera roll.

## Install

1. Install Pythonista
2. In Pythonista, install [StaSH][stash]
3. In a StaSH console, install youtube-dl:

    ```sh
    $ pip install youtube-dl
    ```

4. and clone this repository (note: `git` is only available if StaSH is run in
   Python 2):

    ```sh
    $ git clone https://github.com/Roman2K/youtube-dl-ios
    ```


## Usage

1. Copy a YouTube URL.
2. Run the script.
3. Select a format to download. To save to camera roll, select an AVC format.
4. Tap on the share button to save the file.

[youtube-dl]: https://rg3.github.io/youtube-dl/
[pythonista]: http://omz-software.com/pythonista/
[stash]:https://github.com/ywangd/stash
