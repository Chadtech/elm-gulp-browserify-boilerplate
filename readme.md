# HI THERE

This is my 

# Elm Gulp Browserify Boilerplate

Its basically a template development environment with all of my favorite dependencies. It also might be useful to look at, if you are learning how to use Elm.

How to get going..
```
> git clone https://github.com/Chadtech/elm-gulp-browserify-boilerplate new-project
> cd new-project
> npm install
> elm package install
> gulp

then open up http://localhost:2984
```


This repo is organized as ..
```
dist/         -- Your production-ready app
dev/          -- Your development app
  index.html
  assets/     -- Where you can put images, fonts, etc.
source/       -- Source files
  app.js      -- Loads your elm file, and handles ports
  Main.elm
  *.elm
  main.styl   -- First style file, concat([main.style, .. ])
  View/
    Main.elm  -- Your main view file
    point.styl
    input-field.styl
gulpFile.js
server.js

