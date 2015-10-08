# savepass [![Build Status](https://travis-ci.org/chester1000/savepass.svg)](https://travis-ci.org/chester1000/savepass) [![npm version](https://badge.fury.io/js/savepass.svg)](http://badge.fury.io/js/savepass) [![Dependency Status](https://david-dm.org/chester1000/savepass.svg)](https://david-dm.org/chester1000/savepass) [![peerDependency Status](https://david-dm.org/chester1000/savepass/peer-status.svg)](https://david-dm.org/chester1000/savepass#info=peerDependencies)



This is a CLI tool managing preparing, encrypting and saving (to cloud) password/sensitive text files.

## Download

```
$ npm i -g savepass
```

## Usage

You can either pass CLI flags or answer questions.

```
$ savepass --help

  CLI tool archiving your keybase.io-encrypted data to Google Drive

  Usage: savepass <command>

  where <command> is one of:
      add, new, list, ls, remove, rm

  Example Usage:
      savepass add [OPTIONAL <flags>]
      savepass --debug ls
      savepass rm --file=myBank

  Global flags:
      --debug
          Enable debug output.

  savepass add flags:
      --template=<templateName>
          Specify template name to be used. Available templates can be
          found in `templates/` folder.
      --keybase-user=<keybaseUsername>
          Encrypt output file for a different user then the one logged in.
      --name, --website, --login, --password, --email, --seed
          Pass values from CLI or disable by passing null or false.
          NOTE: --password flag can only be disabled

  Specify configs in the json-formatted file:
      /Users/mee/.config/savepass/config.json

```

## Bugs and feedback

If you discover a bug please report it [here](https://github.com/chester1000/savepass/issues/new).

Mail me at mee DOT damian AT gmail THAT-LITTLE-ROUND-THING com, on twitter I'm [@meeDamian](http://twitter.com/meedamian).


## Licence

MIT @ [Damian Mee](http://meedamian.com)
