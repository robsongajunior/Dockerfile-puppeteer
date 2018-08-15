# Dockerfile-puppeteer
(Puppeteer)[https://github.com/GoogleChrome/puppeteer] is a NodeJS library which provides a high-level API to control Chrome or Chromium over the DevTools Protocol. Puppeteer runs headless by default, but can be configured to run full (non-headless) Chrome or Chromium.


## OBJECTIVE REPO
This repo contains the respective dependencie to be able to run the Puppeteer module into docker container


## HOW TO BUILD IMAGE
```bash
docker build -t docker-puppeteer -f Dockerfile.puppeteer
```

## USING docker-puppeteer image IN YOUR DOCKERFILE
```bash
FROM docker-puppeteer

[self dockerfile configuration]
```
