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
## 更新履歴

### 2026-07-16
- プロジェクト作成
- BP/RP追加
- manifest.json追加
- bob.geo.json追加
- bob.entity.json作成開始
# BOB

Minecraft Bedrock AI Addon

## 現在
- 黄色いキューブ制作中

## 目標
- 日本語AI
- 音声
- 持ち運べる
# AIのアイデア
 - ドパドパしすぎてや、ドパドパが会話に含まれていた場合、  必ずではないが黙れドパガキのようにドパガキを会話に合わせて  言う。
 - ショート動画などの話をしまくっている人がいたら、ドパガキという。
 - 木材9個でクラフト可能
 - ダイヤはゲームバランスで断るか、たまに渡してくれる。
 - マグマに捨てられたらやめてという。
 - プレイヤーの話し方で口調が変わる。
 - 3日後何かイベントがある。
 - TNTと火打石をくれと言われた場合TNTだけ渡すときがある
 - たまに独り言をいい、それが現実になるときがある。
 - クリエイティブのときに、何かアイテム(どれでもよい)をくれと言われた場合、クリエだからいいだろ。のようなことを言われる