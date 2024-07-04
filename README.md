# jekyll-template
Use this template to create a simple Jekyll site for your project.

## Get the code
Use the following one-liner to clone the repository and initialize the jekyll site.
```
sh -c "$(curl -fsSL https://kaangiray26.github.io/jekyll-template/install)"
```

## Running locally
```
docker run --rm --volume="$PWD:/srv/jekyll" -p 4000:4000 -it jekyll/jekyll jekyll serve --livereload --watch
```

## Building with Docker
```
docker run --rm --volume="$PWD:/srv/jekyll" -it jekyll/jekyll jekyll build -d docs
```