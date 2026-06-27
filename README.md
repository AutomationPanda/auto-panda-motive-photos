# Auto Panda Motive Photos

This repository contains image assets for the _Auto Panda Motive_ website.

* Website URL: https://autopandamotive.com/
* Website Repository: https://github.com/AutomationPanda/auto-panda-motive

It serves images through [jsDelivr](https://www.jsdelivr.com/), an open source CDN.
Access images at:

```
https://cdn.jsdelivr.net/gh/AutomationPanda/auto-panda-motive-photos/<filepath>
```

> [!WARNING]
> jsDelivr limits package size (meaning GitHub repository size) to 150 MB.
> It also limits single files to 20 MB.
> If this repository grows too big or if individual images are too big,
> then jsDelivr will fail to serve them.

This repository also provides a [shell script to convert image files to optimized WebP files](./scripts/images-to-webp.sh)
in order to keep image sizes as small as possible.
For this site, optimized images are preferred over high-resolution images
to keep package sizes well under jsDeliver and GitHub Pages limits.
