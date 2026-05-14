# cafe-slim

A-Frameを使用して構築された、SLIM The Coffee Resortカフェの3Dモデルを表示するウェブベースの3Dビューアーです。

## デモ

https://code4fukui.github.io/cafe-slim/

## 機能

- SLIM The Coffee Resortカフェの詳細な3Dモデルを探索できます。
- 標準的なデスクトップ操作、またはVRのテレポート機能を使用してシーン内を移動できます。
- オブジェクトとのインタラクション: カウンターにあるケーキをクリックすると、カフェの公式サイトにアクセスできます。

## 使い方と操作

ウェブブラウザで[デモページ](https://code4fukui.github.io/cafe-slim/)を開いてください。より没入感のある体験を得るには、VRデバイスの使用を推奨します。

### デスクトップ
- **マウス:** 周囲を見渡します。
- **WASDキー:** 前、左、後ろ、右に移動します。

### VR
- **テレポート:** コントローラーで狙いを定め、トリガーボタンを押すと新しい場所に移動します。

## 技術的詳細

- **フレームワーク:** [A-Frame](https://aframe.io/)
- **3Dモデル:** `cafe-slim.glb`, `cafe-slim-cake-reduced-jpg.glb`
- **コントロール:** `aframe-teleport-controls`, `wasd-controls-mode2`

## ライセンス

MIT License — 詳細は[LICENSE](LICENSE)を参照してください。
