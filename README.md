# Welcome!

This is the personal webiste of Brian O'Byrne built with [Jekyll](https://jekyllrb.com/) and hosted using [GitHub Pages](https://pages.github.com/).

You can view the site [here](https://3riano3yrne.github.io/).

## Local Dev
Install Jekyll and Ruby following the [instructions for your OS](https://jekyllrb.com/docs/installation/)
[Mac OS installation](https://jekyllrb.com/docs/installation/macos/)

In the Gemfile make sure the following gems are commented out/in
```ruby
gem "jekyll", "~> 4.3.4"
...
...
# gem "github-pages", group: :jekyll_plugins
```

 if needed, run: `bundle install`

run: `bundle exec jekyll serve`
go to: http://localhost:4000

## Deployment

Deployment happens automatically as commits are merged into 'main' branch.

