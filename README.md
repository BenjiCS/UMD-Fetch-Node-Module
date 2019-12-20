# How to install

```bash
npm i @BenjiCS/node-fetch
```

## How to use

```bash
let nodeFetch = require("./umd");

nodeFetch.init({
  address: "https://YOUR.API/LINK",
  key: "1234"
});

nodeFetch.del("1").then(result => console.log(result));

```