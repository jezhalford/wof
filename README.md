WOF
===

Window On File

    usage: wof [-h] [-a A] [-b B] [FILE]

    Show specified lines from a file.

    positional arguments:
      FILE        The file whose lines you want to see

    optional arguments:
      -h, --help  show this help message and exit
      -a A        The starting line number (Optional - defaults to the first line)
      -b B        The ending line number (Optional - defaults to the last line)
      --line-nums  Show line numbers


Example:

    wof -a 10 -b 20 /path/to/file

## Installation

1. Clone this repository somewhere
2. `cd wof`
3. `sudo ln -s ./wof /usr/bin/wof`

You can then run wof by typing `wof`.

## License
See LICENSE in this repository
