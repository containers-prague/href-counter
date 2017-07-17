# href-counter

This is forked repo of https://github.com/alexellis/href-counter

> A Golang example application which counts internal vs. external hrefs within a page to rate SEO.

The `golang.org/x/net/html` package is used to iterate through all the HTML tokens in the web-page. It provides a working example of parsing HTML piece-by-piece. 

This can be built with the Dockerfile in the repository or through `go get`.

### Build

```
docker build -t href-counter . -f Dockerfile.multi
```

### Run
```
docker run -e url=http://prgcont.cz href-multi  
```
