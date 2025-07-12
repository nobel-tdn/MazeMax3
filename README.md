# MAZEMAX 3

A Neon Labyrinth Bullet-Hell Shooter

---

## 概要

MAZEMAX 3は、迷路探索と弾幕シューティングが融合したネオン風アクションゲームです。React + p5.js + TypeScript + Viteで構築されています。

---

## ディレクトリ構成・主要ファイル

- `App.tsx` ... UIのエントリーポイント、画面遷移・HUD管理
- `components/GameCanvas.tsx` ... ゲーム本体ロジック（p5.js）
- `index.tsx` ... Reactアプリのエントリーポイント
- `index.html` ... HTMLテンプレート
- `constants.tsx` ... アイコンや定数定義
- `types.ts` ... 型定義
- `sounds/` ... 効果音・BGM格納ディレクトリ
- `public/GO.png` ... GameOver画面用画像

---

## セットアップ・起動方法

**前提:** Node.js

1. 依存パッケージのインストール
   ```bash
   npm install
   ```
2. 開発サーバー起動
   ```bash
   npm run dev
   ```
3. ブラウザで `http://localhost:5173` へアクセス

---

## 製作者

NOBEL

---

## サウンド・BGM クレジット

- 効果音ラボ　https://soundeffect-lab.info/
- 無料効果音で遊ぼう！ https://taira-komori.jpn.org/
- DOVA -んぃん様- https://dova-s.jp/bgm/play9598.html
- ファミコン風オリジナルフリーBGM しーでんでん様 https://seadenden-8bit.com/se.html
- Hhowling-Indicator様 https://howlingindicator.net/8bit-2/

---

## ライセンス

本プロジェクトはMITライセンスです（一部サウンド素材を除く）。
