# bitbar-upbank

[![MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://github.com/jakehwll/bitbar-upbank/blob/master/LICENSE.md)
[![Python](https://img.shields.io/badge/Python-3.6-brightgreen.svg)](https://python.org/)

This plugin shows your balance from your UpBank account.

<img src="https://i.imgur.com/vEoGKIQ.png"/>

## Installation

1. Install [Bitbar](https://getbitbar.com/)
2. Install Python 3.6+, you might need to restart.
3. Drag `upbank.10m.py` to your `bitbar_plugins` folder.
4. Edit the `upbank.10m.py` file to contain your UpBank token.
5. Open Bitbar and press CMD + R.

## Debugging

```
> Couldn't posix_spawn: error 8
Make sure you have Python installed.
```
```
> Requests was not found??
$ sudo /Library/Developer/CommandLineTools/usr/bin/python3 -m pip install requests
```

## License

See `LICENSE.md` for details on that.