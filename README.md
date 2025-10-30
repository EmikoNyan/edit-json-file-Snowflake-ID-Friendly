# edit-json-file Snowflake Id Friendly



## What I want to do:
```js
const editJsonFile = require("edit-json-file")

let file = editJsonFile(`${__dirname}/data.json`)

file.set("451445988612374539", {}) //It's a user id from Discord
file.save()
```

## Original version's result:
```json
{
 "451445988612374500": {}
}
```

## My personal version's result:
```json
{
 "451445988612374539": {}
}
```
