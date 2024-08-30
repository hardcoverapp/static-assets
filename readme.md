This repository contains all static assets required for [Hardcover](https://hardcover.app) to run. In development mode, this will use the versions of these images from GitHub Pages. On staging and production we, we use the Google Cloud Bucket versions of these images, routed through Cloudflare's R2 CDN.

To keep deploys fast, these images shouldn't be included in the Hardcover repository itself. Currently this repo is already 70mb and will no doubt grow.

Whenever we need to add a new file to this repository, Adam should also sync it to the Staging and Production Google Cloud buckets.