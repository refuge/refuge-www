# refuge-www

Refuge Website files.

## How to build

First install nanoc and its dependencies with the `contrib/install_nanoc.sh` script.
It will install nanoc, then adsf (used bu nanoc view) and kramdown (to support markdown pages).

Once nanoc is there, you can go to the `site` directory and launch `nanoc` to compile it into
the `output` directory.
If you want to see the site into a quick server, use `nanoc view` and it will open a port 3000
on localhost. This is only opening a web server: you still need to execute `nanoc` each time
you modify anything (recompiling) to see the changes.

## How to deploy

TBD
