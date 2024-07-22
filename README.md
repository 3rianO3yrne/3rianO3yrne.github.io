# Welcome!

This is the personal webiste of Brian O'Byrne built with [Jekyll](https://jekyllrb.com/) and hosted using [GitHub Pages](https://pages.github.com/).

You can view the site [here](https://3riano3yrne.github.io/).

## Local Dev
Install Jekyll and Ruby following the [instructions for your OS](https://jekyllrb.com/docs/installation/)

[Mac OS installation](https://jekyllrb.com/docs/installation/macos/)

Modify the Gemfile like so:
> TODO: there must be a better way to do this

Comment out the GitHub Pages line: `gem "github-pages", "~> 231", group: :jekyll_plugins` 

Uncomment the jekyll line: `gem "jekyll", "~> 4.3.3"` 

If you want to use GitHub Pages, remove the "gem "jekyll"" above and
uncomment the line below

run: `bundle exec jekyll serve`
go to: http://localhost:4000

## Deployment

Deployment happens automatically as commits are merged into 'main' branch.

