# [Rafael Rosa Fu blog](http://rafaelrosafu.info)

## Install:
Assuming you're running on, at least, Ruby 1.9.3, clone the repo, then:
```
bundle install
```

I recommend installing local gems and binstubs:
```
bundle install --path=_vendor --binstubs
```
Just remember to always call `bin/<comand>`, like `bin/jekyll`, `bin/rake` when using binstubs.

## Generate the static site

```
bundle exec jekyll build
```

## License

See [LICENSE](https://github.com/grokpodcast/site/blob/master/LICENSE.md)
