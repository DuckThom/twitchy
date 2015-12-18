# # Twitchy

## Installation:
1. Clone this repository
2. Run `git submodule init; git submodule update`
3. Make sure the following python modules are installed `requests`, `json`, `re` `argparse`, `random` and  `m3u8`. If one or more are missing, they can be installed using `python-pip` (`sudo pip install <module_name>`)

## Usage:
```
./twitchy [-h] [-na] [-nv] channel_name

positional arguments:
channel_name     Name of the twitch channel

optional arguments:
-h,  --help      Show this help message and exit
-na, --no-audio  Disable audio (default: enabled)
-nv, --no-video  Disable video (default: enabled)
-v,  --verbose   Show more output (default: disabled)
-s,  --screen    Start the stream in a screen session (default: disabled)
```

