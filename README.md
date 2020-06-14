# hPlayerV2

## About hPlayerV2

hPlayerV2 is an application developed based on the Quasar Framework, through electron packaging, to achieve online playback of hls video streams.
## Features

+ Support video source import
+ Support classified browsing and search
+ Featured multi-window playback mode

## Get Started

```bash
# Install dependencies
yarn install
# Start the development server
yarn electron:serve
# Compile the binary package
yarn electron:build
```

### Customize Configuration

See [Configuration Reference](https://quasar.dev/quasar-cli/quasar-conf-js).

> ### Note
>
> Video source only needs to be imported once, you can re-import or clear the video source in the settings interface

## TODO

-[x] Highlight the current category
-[x] page cache
-[x] Play in a separate window
-[x] Persistent configuration file
-[x] Support import video source
-[] http/https function optimization
