# BitPrice App

BitPrice by [@bitjson](https://twitter.com/bitjson).

## Developing

You need [Sass](http://sass-lang.com/install). Install and run the watch/reload task:

```sh
$ npm install -g gulp
$ npm install
$ gulp serve
```

### Build & Optimize

```sh
$ gulp
```

Build and optimize the current project, ready for deployment.
This includes linting as well as image, script, stylesheet and HTML optimization and minification.

### Performance Insights

```sh
$ gulp pagespeed
```

Runs the deployed (public) version of your site against the [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) API to help you stay on top of where you can improve.

### Deploy to gh-pages

```sh
$ gulp deploy
```

This builds for production, then deploys the dist folder to gh-pages.
