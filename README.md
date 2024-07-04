# jekyll-template
Use this template to create a simple Jekyll site for your project.

## Running locally
```
docker run --rm --volume="$PWD:/srv/jekyll" -p 4000:4000 -it jekyll/jekyll jekyll serve --livereload --watch
```

## Building with Docker
```
docker run --rm --volume="$PWD:/srv/jekyll" -it jekyll/jekyll jekyll build -d docs
```