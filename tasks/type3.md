## `type = 3`

> Kill **`value[2]` `value[3]`** using the **`values[5]`**.

> Kill **`value[2]` `value[3]`**.

```ts
enum Factions {
  Humans = 1,
  Terminids = 2,
  Automatons = 3,
  Illuminate = 4,
};

const faction: Factions = values[0];
const amount: number = values[2];
const enemyID: number = values[3];
const stratagemNeeded: number = values[4];
const stratagem: number = values[5];

const desc = stratagemNeeded === 1
  ? `Kill <i=1>${amount} ${faction}</i> using the <i=1>${getStratagemName(stratagem)}</i>.`
  : `Kill <i=1>${amount} ${faction}</i>.`;
```

### Examples:

> Kill **10 Stalkers**.
```json
{
  "id": 3332462352,
  "progress": [0],
  "expiresIn": 46806,
  "setting": {
    "type": 2,
    "overrideTitle": "",
    "overrideBrief": "",
    "taskDescription": "",
    "tasks": [
      {
        "type": 3,
        "values": [
          2, // <-- faction: Terminids
          1,
          10, // <-- amount
          2387277009, // <-- enemy ID: Stalker
          0, // <-- any method
          0, // <-- stratagem ID: None
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

> Kill **40 Enemies** using the **EAGLE CLUSTER BOMB**.
```json
{
  "id": 946477370,
  "progress": [0],
  "expiresIn": 46798,
  "setting": {
    "type": 2,
    "overrideTitle": "",
    "overrideBrief": "",
    "taskDescription": "",
    "tasks": [
      {
        "type": 3,
        "values": [
          0, // <-- faction: None
          1,
          40, // <-- amount
          0, // <-- enemy ID: None
          1, // <-- requires stratagem
          1220665708, // <-- stratagem ID: EAGLE CLUSTER BOMB
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

> Kill **200 Enemies** using the **Stalwart**.
```json
{
  "id": 949883092,
  "progress": [0],
  "expiresIn": 46799,
  "setting": {
    "type": 2,
    "overrideTitle": "",
    "overrideBrief": "",
    "taskDescription": "",
    "tasks": [
      {
        "type": 3,
        "values": [
          0, // <-- faction: None
          1,
          200, // <-- amount
          0, // <-- enemy ID: None
          1, // <-- requires stratagem
          1978117092, // <-- stratagem ID: Stalwart
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

> Kill **400 Automatons**.
```json
{
  "id": 3486215587,
  "progress": [0],
  "expiresIn": 46799,
  "setting": {
    "type": 2,
    "overrideTitle": "",
    "overrideBrief": "",
    "taskDescription": "",
    "tasks": [
      {
        "type": 3,
        "values": [
          3, // <-- faction: Automatons
          1,
          400, // <-- amount
          0, // <-- enemy ID: None
          0, // <-- requires stratagem
          0, // <-- stratagem ID: None
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

> Kill **25 Hunters**.
```json
{
  "id": 2794990445,
  "progress": [0],
  "expiresIn": 46802,
  "setting": {
    "type": 2,
    "overrideTitle": "",
    "overrideBrief": "",
    "taskDescription": "",
    "tasks": [
      {
        "type": 3,
        "values": [
          2, // <-- faction: Terminids
          1,
          25, // <-- amount
          3330362068, // <-- enemy ID: Hunter
          0, // <-- requires stratagem
          0, // <-- stratagem ID: None
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

> Kill **30 Enemies** using the **ORBITAL 120MM HE BARRAGE**.
```json
{
  "id": 5488478,
  "progress": [0],
  "expiresIn": 46799,
  "setting": {
    "type": 2,
    "overrideTitle": "",
    "overrideBrief": "",
    "taskDescription": "",
    "tasks": [
      {
        "type": 3,
        "values": [
          0, // <-- faction: None
          1,
          30, // <-- amount
          0, // <-- enemy ID: None
          1, // <-- requires stratagem
          2928105092, // <-- stratagem ID: ORBITAL 120MM HE BARRAGE
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

> Kill **50 Enemies** using the **Autocannon**.
```json
{
  "id": 3365858700,
  "progress": [0],
  "expiresIn": 46811,
  "setting": {
    "type": 2,
    "overrideTitle": "",
    "overrideBrief": "",
    "taskDescription": "",
    "tasks": [
      {
        "type": 3,
        "values": [
          0, // <-- faction: None
          1,
          50, // <-- amount
          0, // <-- enemy ID: None
          1, // <-- requires stratagem
          841182351, // <-- stratagem ID: Autocannon
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