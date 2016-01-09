pb.co.za
========

This repo contains the source code of my personal website which serves as a public home for my creative output.

Getting the source code
-----------------------

The source code for this repo should be available on [github](https://github.com/pieterbreed/pb.co.za).

`git clone --recursive git@github.com:pieterbreed/pb.co.za.git`

Verifying the authenticity of the content
-----------------------------------------

I am using git-based GPG signing. You can verify a commit in the normal way, like this:

```
```

Content License
---------------

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">pb.co.za</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://pb.co.za/" property="cc:attributionName" rel="cc:attributionURL">Pieter Breed</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

The full text of the license can be found inside this repo in a file called `LICENSE.md`.

Setup Hugo
----------

This is a [hugo](http://gohugo.io) site. You'd need to install that before you can render the HTML.

```
$ brew info hugo
hugo: stable 0.15 (bottled), HEAD
Configurable static site generator
https://gohugo.io/
Not installed
From: https://github.com/Homebrew/homebrew/blob/master/Library/Formula/hugo.rb
==> Dependencies
Build: go ✔

$ brew install hugo
==> Downloading https://homebrew.bintray.com/bottles/hugo-0.15.el_capitan.bottle.tar.gz
######################################################################## 100.0%
==> Pouring hugo-0.15.el_capitan.bottle.tar.gz
==> Caveats
Bash completion has been installed to:
  /usr/local/etc/bash_completion.d
==> Summary
🍺  /usr/local/Cellar/hugo/0.15: 29 files, 16M

$ which hugo
/usr/local/bin/hugo

$ hugo version
Hugo Static Site Generator v0.15 BuildDate: 2015-11-26T08:29:07+02:00
```
