---
template: homepage.html
title: Umbra Sphere
---

<style>
.page-header {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 0.5em;
}

.page-header::before {
    display: inline-block;
    content: image-set('/app-icon-64x64@1x.png' 1x, '/app-icon-64x64@2x.png' 2x, '/app-icon-64x64@3x.png' 3x);
}

.subtitle {
    text-align: center;
}
</style>

![Screenshots](/screenshots.webp)

<div class="subtitle">

Discover the world, with the power of [S²Geometry](http://s2geometry.io).

[![](https://toolbox.marketingtools.apple.com/api/v2/badges/download-on-the-app-store/black/en-us)](https://apps.apple.com/app/id6753129532)

</div>

## System Requirements
- macOS Sequoia or above
- iOS 18 or above

## Open Source
- [Umbreon for Swift](https://github.com/lucka-me/umbreon-swift): Core components of Umbra Sphere.
- [Sphere Geometry for Swift](https://github.com/lucka-me/sphere-geometry-swift): Fundamental implementation of S²Geometry in Swift.
- [Falinks](https://github.com/lucka-me/falinks): A command line tool to collect data of administrative regions from OpenStreetMap and Wikidata, and build database and S²Geometry Covers used by Umbra Sphere.