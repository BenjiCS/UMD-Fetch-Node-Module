
![](https://img.shields.io/npm/v/@benjics/nodefetch?style=flat-square)
![](https://img.shields.io/bundlephobia/min/@benjics/nodefetch?label=Install%20Size&style=flat-square)
![](https://img.shields.io/npm/l/@benjics/nodefetch?style=flat-square)
![](https://img.shields.io/jsdelivr/npm/hy/@benjics/nodefetch?label=Downloads&style=flat-square)

# NodeJS Fetch

Fetch Wrapper that can Fetch Promises in varius ways like brower, XMLHttpRequest or NodeJS

Includes methods: Post, Get, Delete, Put


## How to install

1.    `npm install`

2.    Locate the YOURFLILE.js folder

3.    In the nodeFetch function shown below, Place the address you want to Fetch


## How to use

```javascript
if (typeof exports === "object") {
  var nodeFetch = require("@benjics/nodefetch");
}

nodeFetch.init({
  address: "https://YOUR.API/LINK", // Here you set your link to your fetch address
  key: "1234" // Here you set your key to your api If you have one
});

nodeFetch.get("1").then(result => console.log(result));
```

## How to use in a browser

Set this in your html file

```html
<script src="https://unpkg.com/@benjics/nodefetch@0.1.0/umd.js" defer></script>
```
And then add the javascript file you made with "how to use" section under the script showed above
