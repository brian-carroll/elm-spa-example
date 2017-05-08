# ![RealWorld Example App](https://github.com/gothinkster/realworld/raw/master/media/realworld.png)

> ### [Elm](http://elm-lang.org) codebase containing real world examples (CRUD, auth, advanced patterns, etc) that adheres to the [RealWorld](https://github.com/gothinkster/realworld-example-apps) spec and API.


### [Demo]()&nbsp;&nbsp;&nbsp;&nbsp;[RealWorld](https://github.com/gothinkster/realworld)


This codebase was created to demonstrate a fully fledged fullstack application built with [Elm](http://elm-lang.org) including CRUD operations, authentication, routing, pagination, and more.

For more information on how to this works with other frontends/backends, head over to the [RealWorld](https://github.com/gothinkster/realworld) repo.

# How it works

Check out [the full writeup](https://dev.to/rtfeldman/tour-of-an-open-source-elm-spa)!

# Getting started

If you don't already have `elm` and `elm-live`:

> npm install -g elm elm-live

Then, to build everything:

> elm-live --output=elm.js src/Main.elm --pushstate --open --debug

(Leave off the `--debug` if you don't want the time-traveling debugger.)
