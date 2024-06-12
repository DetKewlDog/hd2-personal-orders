## `type = 4`

> Complete **`values[2]` `values[3]` Objectives**.

> [!WARNING]
> More info on `values[3]` needed!

```ts
enum ObjectiveType {
  Secondary = 2,
};

const amount: number = values[2];
const objectiveType: ObjectiveType = values[3];
```

### Examples:

> Complete **6 Secondary Objectives**.
```json
{
  "id": 4254162676,
  "progress": [0],
  "expiresIn": 46798,
  "setting": {
    "type": 2,
    "overrideTitle": "",
    "overrideBrief": "",
    "taskDescription": "",
    "tasks": [
      {
        "type": 4,
        "values": [
          0,
          0,
          6, // <-- amount
          2, // <-- objective type
          0,
          0,
          0,
          0
        ],
        "valueTypes": [
          1,
          2,
          3,
          7,
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