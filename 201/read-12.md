## Chart.js API

- Charts are better than tables... easy to look at and convey data quickly.
- Chart.js is a javascript plugin that makes it easier to work with charts in js.
- You need to download and import the Chart.js file in order to use it in your code.
- Asgn an id, width, and height. Use pull from the DOM to access the 'canvas' tag.
- All that's required is the script included in your page along with a single \<canvas> node to render the chart.

---

## Basic Usage

- The \<canvas> element has only two attributes, width and height. Both are optional and can also be set using DOM properties. 
- ***If your renderings seem distorted, try specifying your width and height attributes explicitly in the \<canvas> attributes, and not using CSS.***
- When no styling rules are applied to the canvas it will initially be fully transparent.
- It is easy to define some fallback content for older browsers, and you should always provide it
- getContext() takes one parameter, the type of context.
- 1 unit in the grid corresponds to 1 pixel on the canvas.
- A path is a list of points, connected by segments of lines that can be of different shapes, curved or not, of different width and of different color.

---

- [Reading Notes Home](https://vektur.github.io/reading-notes/)