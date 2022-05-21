# @kjn/svg-minimap

Creates a zoomable, pannable minimap component for your svg elements.

## How to use

Install this package

```sh
npm install @kjn/svg-minimap
```

Import and initialise the minimap

```js
import SvgMinimap from "@kjn/svg-minimap";

new SvgMinimap(document.getElementById("svg"), document.getElementById("minimapContainer"));
```

Assuming that we have a `<svg>` element that contains various svg drawings.
AND that there exists a preferably bounded container where the minimap should be placed into.
