# Xhisk

シングルファイル（`index.html`）で動作する、アイドル運営シミュレーション UI です。

## ファイル構成

```text
.
├── index.html        # アプリ本体（UI / ロジック）
├── package.json      # 開発用スクリプト
└── README.md
```

## 初期セットアップ

前提:
- Node.js 18 以上
- npm 9 以上

```bash
npm install
```

> このプロジェクトは外部依存パッケージを持たないため、`npm install` は主に `package-lock.json` の生成と将来拡張のための初期化です。

## ローカル起動

```bash
npm run start
```

起動後、ブラウザで以下へアクセス:

- <http://localhost:5173>

## 補足

- Tailwind CSS は CDN 経由で読み込みます。
- ビルド工程はなく、`index.html` を直接編集すれば動作確認できます。
