Download episodes of Fetch! with Ruff Ruffman on the terminal, directly from the PBS Kids website!

Note: Episodes 404 "Ruff Pigs Out and Has a Whale of a Time" and 505 "The Ol' Shell Game" are not available for download.

Prerequisites
=============
*ffmpeg
*curl
*python (2 or 3)
*git (optional)

If not pre-installed, all three of these can be installed quickly using [brew][1], [apt-get][2], or [chocolatey][3].  Run `(brew install/sudo apt-get install/cinst) ffmpeg curl python git`

Note: Mac already includes curl, python, and git, so there is no need to install these using brew.

Additional note: Ubuntu felt the need to rename ffmpeg and make changes to it.  To install the actual ffmpeg, run `sudo apt-add-repository ppa:jon-severinsson/ffmpeg;sudo apt-get update` before attempting to install ffmpeg.

How to run
==========
First, run git clone https://github.com/iggyvolz/fetch-dl.git and cd into it (or download the script [directly][4]).  Then, you may simply run `./fetch-dl [episode number] [output file]` (Windows users and Mac/Linux users with Python installed elsewhere than /usr/bin/python should use `python fetch-dl [episode number] [output file]`).  You can also move fetch-dl into your $PATH to run it anywhere!

Note: Has not been tested on Windows.  Windows support is experimental as I don't have a Windows computer.  Feel free to report issues or make pull requests.

[1]: http://brew.sh
[2]: http://www.ubuntu.com/
[3]: http://chocolatey.org/
[4]: https://raw.githubusercontent.com/iggyvolz/fetch-dl/master/fetch-dl
