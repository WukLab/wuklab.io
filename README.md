## Installation and Usage

### Ubuntu
install jekyll by:
https://jekyllrb.com/docs/installation/ubuntu/

install bundle
```
bundle install
```

After making your modifies,
build and run your website in localhost by:
```
bundle exec jekyll server
```
Then visit localhost:4000 in your explorer

replace _site directory with wuklab.github.io and upload

Visit a new Wuklab!

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
