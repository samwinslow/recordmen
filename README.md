# The Record Men

## Technologies used
So far:

- Static HTML
- Bootstrap framework with Less, compiles to static CSS


## Build instructions for development
1. First, you'll need an Apache/MySQL/PHP server running on your computer: make sure to `sudo apachectl start`.
2. You'll also need Less, consult [their docs](http://lesscss.org/#using-less-installation) for installation information. You don't have to worry about Less.js, we only care about the command line.
3. Look over compile.sh and make sure your server directory is set correctly. On Linux it is most likely `/var/www`, on OSX it may be `~/Sites` or `/Library/WebServer/Documents`.
***compile.sh will overwrite anything in that directory before copying by default!***

To compile, run `./compile.sh` from your repository's directory. You'll be prompted for your password.
