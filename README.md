# download-sanitizer #

## debrand-download ##

Remove tags and sanitize the filenames of release group downloads.

Branding and information tags are stripped, and an attempt is made to standardize the format of the season and episode identifier (ie: `S01E08`).

**eg**:
* `The Last Man on Earth 720p [2HD] [AFG].mkv` -\> `The Last Man on Earth.mkv`
* `The Beverly Hillbillies s1e4 [LOL] (AC3).mp4` -\> `The Beverly Hillbillies S01E04.mp4`

### SYNOPSIS ###

`debrand-download [option] file(s)`

### OPTIONS ###

* `debrand-download -t file(s)` | `--test file(s)`: View the changes without making them
* `debrand-download -h` | `--help`: Display this help

### EXAMPLES ###

* `debrand-download *`: Run on all files in the directory
* `debrand-download *.mp4`: Run on all files ending in .mp4
* `debrand-download file1 file2`: Run on 'file1' and 'file2'
* `debrand-download -t file1 file2`: See how file1 and file2 would change

## timecode-download ##

Add the playback time of a media file to the end of its filename.

**eg**: `The Last Man on Earth.mkv` -> `The Last Man on Earth [1h26m].mkv`

### SYNOPSIS ###

`timecode-download [option] file(s)`

### OPTIONS ###

* `timecode-download -t file(s)` | `--test file(s)`: View the changes without making them
* `timecode-download -h` | `--help`: Display this help

### EXAMPLES ###

* `timecode-download *`: Run on all files in the directory
* `timecode-download *.mp4`: Run on all files ending in .mp4
* `timecode-download file.avi file.mkv`: Run on 'file.avi' and 'file.mkv'
* `timecode-download -t file.avi file.mkv`: See how file.avi and file.mkv would change

## CREDITS ##

Written by Kevin MacMartin: [GitHub Projects](https://github.com/prurigro?tab=repositories) | [Arch Linux AUR Packages](https://aur.archlinux.org/packages/?SeB=m&K=prurigro)

## LICENSE ##

This script is open source and licensed under the [GPLv3](http://www.gnu.org/copyleft/gpl.html).
