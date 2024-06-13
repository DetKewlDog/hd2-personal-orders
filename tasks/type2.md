## `type = 2`

> Successfully extract with **`values[2]` `values[5]` Samples**.

```ts
enum SampleRarities {
  Common = 3992382197,
  Rare = 2985106497,
};

const amount: number = values[2];
const sample: SampleRarities = values[5];
const sampleName = SampleRarities[sample].toString();

const desc = `Successfully extract with <i=1>${amount} ${sampleName} Samples</i>.`;
```

### Examples:

> Successfully extract with **10 Common Samples**.

```json
{
  "id": 992180888,
  "progress": [0],
  "expiresIn": 46799,
  "setting": {
    "type": 2,
    "overrideTitle": "",
    "overrideBrief": "",
    "taskDescription": "",
    "tasks": [
      {
        "type": 2, // <-- type
        "values": [
          0,
          1, // <-- might be bool for amount
          10, // <-- amount
          0,
          1, // <-- might be bool for specific sample type
          3992382197, // <-- sample
          0,
          0,
          0,
          0
        ],
        "valueTypes": [
          1,
          2,
          3,
          4,
          6,
          5,
          8,
          9,
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