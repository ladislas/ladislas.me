# ladislas.me

## Quick Start Install

```
# clone the repo
$ git clone --recursive https://github.com/ladislas/ladislas.me

# downloand and unzip the latest ghost
$ curl -L https://ghost.org/zip/ghost-latest.zip -o ghost.zip
$ unzip -uo ghost.zip -d ghost

# rsync the content of the latest release with our blog
$ rsync -rabu ghost/ ladislas.me

# install node modules
$ npm install --production

# launch the server
$ npm start - to test on local environment
$ npm start --production - for production

# visit the following to make sure it works
$ http://localhost:2368/ghost :tada:
```

More [install docs](http://support.ghost.org/installation/) here in case you got stuck.

## Copyright & License

Copyright (c) 2013-2017 Ghost Foundation - Released under the [MIT license](LICENSE).
