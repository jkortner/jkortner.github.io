# jkortner.github.io

Personal website made with [Jekyll](http://jekyllrb.com) using the [Compass](http://excentris.net/compass/) theme.

[jkortner.github.io](https://jkortner.github.io/)

In order to test the webpage locally, I use [Docker](https://www.docker.com):

```         
docker run --rm --volume="$PWD:/srv/jekyll" -p 4000:4000 -it jekyll/jekyll:latest \
  bash -c "bundle install && bundle exec jekyll serve --watch -H 0.0.0.0"
```
