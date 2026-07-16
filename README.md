chatgpt見れますか？見てれたら「見れたで！」って送ってな。
githubでの進め方
BOB-
├── BP/
├── RP/
├── Server/
├── Docs/
├── README.md
├── LICENSE
└── .gitignore
ファイル構造
BOB/
├── behavior_packs/
│   └── BOB_BP/
│       ├── manifest.json
│       ├── entities/
│       │   └── bob.entity.json
│       ├── scripts/
│       │   ├── main.js
│       │   ├── ai.js
│       │   ├── chat.js
│       │   ├── inventory.js
│       │   └── events.js
│       └── functions/
│
├── resource_packs/
│   └── BOB_RP/
│       ├── manifest.json
│       ├── models/
│       │   └── entity/
│       │       └── bob.geo.json
│       ├── textures/
│       │   └── entity/
│       │       └── bob.png
│       ├── animations/
│       ├── animation_controllers/
│       └── entity/
│           └── bob.entity.json
│
└── server/
    ├── index.js
    ├── ai.js
    ├── voice.js
    └── package.json