## `type = 7`

> Extract from a successful **Mission `values[2]`** times.

> [!WARNING]
> More info on this Order type is needed - "Mission" being bolded leads me to believe it can change.

```ts
const amount: number = values[2];

const desc = `Extract from a successful <i=1>Mission ${amount} times</i>.`;
```

### Examples:

> Extract from a successful **Mission 3** times.
```json
{
  "id": 680227134,
  "progress": [0],
  "expiresIn": 46799,
  "setting": {
    "type": 2,
    "overrideTitle": "",
    "overrideBrief": "",
    "taskDescription": "",
    "tasks": [
      {
        "type": 7,
        "values": [
          0,
          0,
          3, // <-- amount
          0,
          0,
          0,
          0,
          0,
          0
        ],
        "valueTypes": [
          1,
          2,
          3,
          8,
          7,
          9,
          10,
          11,
          12
        ]
      }
    ],
    "rewards": [
      {
        "type": 1,
        "id": 897894480,
        "amount": 15
      }
    ],
    "reward": {
      "type": 1,
      "id": 897894480,
      "amount": 15
    },
    "flags": 0
  }
}
```