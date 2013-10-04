# heroku

heroku files for various projects and scripts to assemble

Warning:
Not all projects are committed to github.
What to do about it?
Make heroku project dir on github for extra files and shell scripts to sync/copy files from repos?
Git submodules?
Perhaps subtree merge strategy is more appropriate?
https://www.kernel.org/pub/software/scm/git/docs/howto/using-merge-subtree.html

Notably:

## boolwidth-explorer
 - heroku: http://boolwidth-explorer.herokuapp.com
 - github: https://github.com/emnh/boolwidth/tree/master/explorer
 - in a github subdir of boolwidth 
 - has extra heroku files in this repo
 - TODO: fix. submodule?

## clue2
 - heroku: http://clue2.herokuapp.com/static/index.html (password protected due to private copy of dictionaries)
 - github: https://github.com/emnh/clue2
 - in a github subdir of clue2
 - has extra heroku files in this repo
 - TODO: fix. subtree merge
 - TODO: password in heroku project setting or something

## himera-emh
 - heroku: http://himera-emh.herokuapp.com/
 - github: https://github.com/emnh/himera
 - fork of: https://github.com/fogus/himera
 - perfect mirror github <-> heroku

## live-cljs
 - fork of: https://github.com/ibdknox/live-cljs
 - no worthwhile changes yet
 - TODO: should create perfect mirror if more changes

## pygments-emh
 - heroku: http://pygments-emh.herokuapp.com/
 - github: https://github.com/emnh/pygments-heroku
 - fork of: https://github.com/rumblelabs/pygments-heroku
 - perfect mirror github <-> heroku

## smooth-td
 - fork of: https://github.com/heroku/clojure-sample
 - at hello world stage
 - not much worthwhile changes yet
 - TODO: create github mirror if more changes
