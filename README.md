# Subl handler using Phpstorm on Linux (Ubuntu based)

Enables Phpstorm to open URL Scheme subl:// and txmt:// like these:

`subl://open/?url=file:///etc/passwd&line=10&column=2`

This is created for laravel error handler, it defaults to subl links to open files, but I use phpstorm, so made few changes to existing subl package from https://github.com/algorich/sublime-url-handler to use the phpstorm

## Installation

Download [latest release](https://github.com/algorich/sublime-url-handler/archive/master.zip).

Unzip it, then:
``` bash
cd sublime-url-handler-master
bash install
```
## Test it

Open a new tab on your browser and type: subl://open/?url=file:///etc/hosts


## Credits

All credits goto owner of https://github.com/algorich/sublime-url-handler since I just made small change to make it work with phpstorm.
