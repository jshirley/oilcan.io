# The Website at http://oilcan.io

## This is a [Middleman](https://middlemanapp.com/) Powered Website

This means you need Ruby to contribute. It's very easy after that.

### For OS X

To get everything up and running, clone this repository and run the following:

```shell
brew install rbenv ruby-build
rbenv install 2.2.0 # Install Ruby 2.2.0 (latest as of this writing)
rbenv global 2.2.0 # Just use this e'rywhere
cd oilcan.io
bundle install
bundle exec middleman
```

### For Linux

WTF? For real? If you run Linux you can setup Ruby.

### For Windows

No.

## Updating Files and Stuff

All the content is in the `source` directory. If you create an `index.html.erb`
in a directory called `foo`, it will be available at
`http://oilcan.io/foo/index.html` (or more beautifully, `http://oilcan.io/foo/`).

Use the layouts! You can have any number of layouts that inherit or stand
alone. Use those for spaces on the site.

## The Future

So... why not use Squarespace? I dunno, shuttup. This lets us host things on a
server we control. There is no silliness to hosting, it's just static files. We
can spin up microservices if we want other fanciness.
