# download-debrander #

This is a simple script for sanitizing the filenames of downloaded files that were named by release groups.

It removes branding and information tags, as well as standardizing the format of the season and episode identifier.

## SYNOPSIS ##

download-debrand [option] files

## OPTIONS ##

* `download-debrand -t` | `--test`: Show the results of the change without changing any files.
* `download-debrand -h` | `--help`: Display help information.

## EXAMPLES ##

* `download-debrand *`: Run on all the files in the current directory.
* `download-debrand *.mp4`: Run on all files in the current directory ending in **.mp4**.
* `download-debrand file1 file2`: Run on 'file1' and 'file2'.
* `download-debrand -t file1 file2`: Show the changes that will be made if run on 'file1' and 'file2'.

## CREDITS ##

Written by Kevin MacMartin:

* [GitHub Projects](https://github.com/prurigro)
* [Arch Linux AUR Packages](https://aur.archlinux.org/packages/?SeB=m&K=prurigro)

## LICENSE ##

Licensed under the [MIT license](http://opensource.org/licenses/MIT).
