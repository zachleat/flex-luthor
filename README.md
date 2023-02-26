# Flex Luthor

A small wrapper library to help with responsive intrinsic-sized Flexbox layouts that wrap based on content and container width (avoiding viewport-based media queries when possible).

## Demo

[https://flex-luthor.zachleat.dev/](https://flex-luthor.zachleat.dev/)

## Installation

Available on [npm](https://www.npmjs.com/package/@zachleat/flex-luthor).

```
npm install @zachleat/flex-luthor --save
```

## Versions

* `v4.0.0`: Margin feature renamed more accurately to Gap: `--fl-margin` is now `--fl-gap`. Gap now defaults to `.5em 1em` (`.5em` vertical, `1em` horizontal). You can reset this to `0` if needed.
* `v3.0.0`: Forked from [`filamentgroup/flex-luthor`](https://github.com/filamentgroup/flex-luthor/) and updated to support Flexbox with `gap`.