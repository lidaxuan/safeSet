# safeSet

``npm i @lijixuan/safe-set``

```
const safeSet = require("@lijixuan/safe-set");
const data = {};
const value = safeSet(data, "a.b.c[1].d", "hello world");

//输出结果
value = {
  "a": {
    "b": {
      "c": [
        null,
        {
          "d": "hello world"
        }
      ]
    }
  }
};

```