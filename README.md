[![CircleCI](https://circleci.com/gh/trueprint/generator-redux-actions.svg?style=shield&circle-token=7a8831f66101d9de0ad55b48eb7f3b6ef163727e)](https://circleci.com/gh/trueprint/generator-redux-actions)

# generator-redux-actions

> Compose large Redux apps with small Redux modules

## Why?

I got tired of typing out the same boilerplate in Redux apps with 20+ submodules.

## Prerequisites

You should be using [redux-actions](https://github.com/acdlite/redux-actions), and optionally [redux-thunk](https://github.com/gaearon/redux-thunk) (see snippet below).

## Getting started

Get [Yeoman](http://yeoman.io/learning/) and this module.

```
$ npm i -g yo
$ npm i generator-redux-actions
```

## Creating a module

```
$ yo @arivale/redux-actions todos --async-actions=true  # create thunks for your actions; need redux-thunk for this!
```

## License

MIT © 2017, Victor Alvarez
