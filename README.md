# Wear Your Damn Mask

[![Netlify Status](https://api.netlify.com/api/v1/badges/059513f5-57e7-452f-b44c-13e18983df5b/deploy-status)](https://app.netlify.com/sites/clever-jang-d57af0/deploys)
![Build Status](https://github.com/corasaurus-hex/wearyourdamnmask/actions/workflows/noon_deploy.yml/badge.svg?event=schedule)

The site build scripts for [https://wearyourdamnma.sk](https://wearyourdamnma.sk).

Patches welcome if you want to add more disturbing facts.

## Build

To build...

``` sh
ruby build.rb
```

This will create the `build/index.html` file.

Or have it watch for file changes and automatically rebuild...

``` sh
bash watch.bash
```

This requires [fswatch](https://github.com/emcrisostomo/fswatch), however.

