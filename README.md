# oebb-cli

Inofficial CLI Client for the Austrian Federal Railways (ÖBB) API. Written by @chrboe with <3 in GoLang. Modified by @bioharz 

[![Build Status](https://travis-ci.com/chrboe/oebb-cli.svg?branch=master)](https://travis-ci.com/chrboe/oebb-cli)


## Build
Install golang https://golang.org/

Build oebb-cli with: `go build`


## Usage

Usage: ./oebb-cli search [from] [to]  [flags]

flags:

    -h, --help          help for search
  
    -n, --results int   Number of search results to display (default 5)
  
    -t, --time string   Departure time

Usage examples:

`./oebb-cli search "Wien Bahnhof" "Graz Hbf" -t 11:00`

`./oebb-cli search "Wien Bahnhof" "Graz Hbf" -t 1100`

`./oebb-cli search "Wien Bahnhof" "Graz Hbf" -t 1100`

## Video demonstration


[![asciicast](https://asciinema.org/a/q5sUksYLTR6nqYzmjc4CFdKxM.svg)](https://asciinema.org/a/q5sUksYLTR6nqYzmjc4CFdKxM)
