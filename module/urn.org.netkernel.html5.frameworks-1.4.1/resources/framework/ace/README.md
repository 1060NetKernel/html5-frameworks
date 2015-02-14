This version of Ace is generated from sources to add support for Turtle and SPARQL and does not really match a release version. The version chosen is approximately what a new release would be. In the future, if the pull requests for those changes are accepted, released versions are acceptable substitutes. Until then, here are the steps for generating a release from the source.

https://github.com/ajaxorg/ace

and then:

npm install in the resulting directory.
npm install in the tool directory (if you want to do anything with the tooling).

and then:

node Makefile.dryice.js full

This will generate the following directories under the build folder:

src
src-min
src-min-noconflict
src-noconflict

Move those to a new directory number under this directory and change the value in the latest file.

