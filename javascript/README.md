# teraflopai-node

## Installation
```bash
npm i teraflopai
```

## Usage
```js
import TeraflopAI from "teraflopai";

const client = new TeraflopAI({
  url: "https://api.caselaw.teraflopai.com/v1/search/free",
});

const result = await client.search("City of Houma");
console.log(result);
```