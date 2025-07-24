# Sera - Jekyll Theme

## System Preparation

To use this project, you'll need the following things installed on your machine.

1. [Jekyll](http://jekyllrb.com/docs/) - `$ gem install jekyll bundler`
2. [Jekyll-Gems](http://jekyllrb.com/docs/) - `$ bundle install`

## Usage

Since this is a Jekyll theme, every command described in the [Jekyll documentation](https://jekyllrb.com/docs/) is avaialable.

### Development

To start the development workflow, run the following which overrides the baseurl in dev so that website can run locally:

```
bundle exec jekyll serve --livereload --config _config.yml,_config_dev.yml
```

### Production

When you commit to prod, it will use _config.yml, which already has baseurl configured for prod, so no changes necessary - just commit to the branch and all will be well

To build the project, run:

```
bundle exec jekyll build
```
