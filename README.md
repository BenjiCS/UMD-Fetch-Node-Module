# How to install

```bash
npm i @BenjiCS/node-fetch
```

## How to use

```bash
let nodeFetch = require("./umd");

nodeFetch.init({
  address: "https://reqres.in/api/users?page=2",
  key: "1234"
});

nodeFetch.del("1").then(result => console.log(result));

```