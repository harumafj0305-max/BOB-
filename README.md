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
# TODO

- [x] GitHub作成
- [x] BPフォルダ作成
- [x] RPフォルダ作成
- [x] manifest.json作成
- [x] bob.geo.json作成
- [ ] bob.png作成
- [ ] bob.entity.json作成
- [ ] Script API実装
- [ ] プレイヤーを見る
- [ ] 拾う機能
- [ ] AI会話
- [ ] 音声