# How to install

```bash
npm i @benjics/nodefetch
```

## How to use

```bash
let nodeFetch = require("@benjics/nodefetch");

nodeFetch.init({
  address: "https://YOUR.API/LINK",
  key: "1234"
});

nodeFetch.del("1").then(result => console.log(result));

```