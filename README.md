#d3

## Description
D3 stands for data-driven documents. 
It is a javascript library for building powerfull data visualization.
D3 allows you to bind arbitrary data to a Document Object Model (DOM), and then apply data-driven transformations to the document.

## Usage
Include the latest version of the d3 library in the html file:
"http://d3js.org/d3.v3.min.js"

D3 also runs on Node.js. Use npm install d3 to install it.

### Selectors
D3 uses CSS selectors for data manipulation in the web document.
```
<body>
<p>Hello World</p>

<script>
  d3.select("p").text("GA prezentation"); // changes the text of the paragraph

  d3.select("body").append("p").text("Wazzup?") // append a new paragraph to the body element
</script>

</body>

```

## Resources
[D3js.org](http://d3js.org)
[D3 docs](https://github.com/mbostock/d3/wiki/API-Reference)
[Tutorial](https://github.com/curran/screencasts/tree/gh-pages/introToD3)



