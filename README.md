# totem-tweet-getter

Tool querying tweets to feed the totem.

See https://github.com/fixme-lausanne/totem

## Install

`npm install -g`

## Usage

```
Usage: tweet-getter

Examples:
  tweet-getter --track hack --lausanne                                 Get every tweets from Lausanne AND containing the word "hack"
  tweet-getter --username Binary_Brain --tags="Javascript, Web Dev"    Get every tweets sent by @Binary_Brain


Options:
  -h, --help      Show this help.                                     [default: false]
  -l, --lausanne  Select tweets from Lausanne.                        [default: false]
  -t, --track     Select tweets containing the given keyword.       
  -u, --username  Select tweets from username.                      
  -i, --userid    Select tweets from userid.                        
  -v, --verbose   Verbose mode.                                     
  -T, --tags      Additional tags for the JSON separated by a comma.
```
