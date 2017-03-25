A dockerized version of [Shopify Theme Kit](https://shopify.github.io/themekit/).

The image is hosted on DockerHub as [jpteasdale/shopify-theme](https://hub.docker.com/r/jpteasdale/shopify-theme/)

To use, run the following from your theme directory. 
```
docker run --rm -it -v ${PWD}:/theme jpteasdale/shopify-theme
```


To run a command, just include it at the end, ie:
```
docker run --rm -it -v ${PWD}:/theme jpteasdale/shopify-theme watch
```
