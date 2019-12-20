# How to install

```bash
npm i @benjics/nodefetch
```

## How to use

```bash
if (typeof exports === "object") {
  var nodeFetch = require("@benjics/nodefetch");
}

nodeFetch.init({
  address: "https://YOUR.API/LINK",
  key: "1234"
});

nodeFetch.del("1").then(result => console.log(result));

```

## How to use in a browser

Set this in the top of your html file
```bash
<script src="https://unpkg.com/@benjics/nodefetch@0.1.0/umd.js"></script>
```
And then add the javascript file you made with "how to use" section under the script above
