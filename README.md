# urlview-weechat

This is a simple [weechat](https://weechat.org/) plugin that allows you
to pipe buffers through [urlview](https://github.com/sigpipe/urlview).
This gives you an interactive list of URLs to open, which is especially
helpful if there are multiple URLs in the buffer making
[urlgrab](https://weechat.org/scripts/source/urlgrab.py.html/) hard to
use.

## Installation

Copy the script to `~/.weechat/python/autoload`

```sh
mkdir -p ~/.weechat/python/autoload
wget https://raw.githubusercontent.com/keith/urlview-weechat/master/urlview.py ~/.weechat/python/autoload
```

This is a python rewrite of [this ruby
plugin](https://weechat.org/files/scripts/unofficial/urlview.rb)
