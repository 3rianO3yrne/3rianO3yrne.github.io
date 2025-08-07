# Welcome!

This is the personal webiste of Brian O'Byrne built with [Jekyll](https://jekyllrb.com/) and hosted using [GitHub Pages](https://pages.github.com/).

You can view the site [here](https://3riano3yrne.github.io/).

## Local Dev
Install Jekyll and Ruby following the [instructions for your OS](https://jekyllrb.com/docs/installation/)
[Mac OS installation](https://jekyllrb.com/docs/installation/macos/)

Run: `bundle install`

Run: `bundle exec jekyll serve`

To view the local site, go to: http://localhost:4000

Press `ctrl-c` to stop the local server.

## Deployment

Deployment happens automatically as commits are merged into 'main' branch.

## Usage

## Create Blog Post
New posts can be created with [jekyll-compose](https://github.com/jekyll/jekyll-compose
).
```
    bundle exec jekyll post "My New Post"
    # or specify a custom format for the date attribute in the yaml front matter
    bundle exec jekyll post "My New Post" --timestamp-format "%Y-%m-%d %H:%M:%S %z"
```
Create drafts
```
    bundle exec jekyll draft "My new draft"

```
Publish drafts:
```
    bundle exec jekyll publish _drafts/my-new-draft.md
```


