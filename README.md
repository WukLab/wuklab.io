# README

## How to update website

It's very simple to make changes: update files in `_data/`,
push to master, and Github will build pages.

If you see something went wrong, grep keyword and check if it's css related.

## How to setup local testing envionment

1. Install jekyll: https://jekyllrb.com/docs/installation/ubuntu/

2. Install bundle
```
bundle install
```

After making your modifies, build and run _locally_:
```
bundle exec jekyll server
```

Then visit `localhost:4000`.

### Mac
https://jekyllrb.com/docs/installation/macos/

## Some tips
Jekyll concatenates the _include directory and makes our webpage

The name is self-explanary, you should be able to modify them.

Some useful guide:

_post: our research section
_include/css/main.css: css global file

More guide to be added.

## Image processing 

resize and crop
```
mogrify -resize "2108x2811^" -gravity Center -crop 2108x2811 *.jpg
```
