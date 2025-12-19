# LivingMesh_SlimeTentacle V1.1  
### Procedural Slime / Tentacle Deformation Shader for Unity & VRChat  
### Unity / VRChat 向け スライム・触手変形シェーダー

**LivingMesh_SlimeTentacle** は、  
任意のメッシュを「生きているスライム・触手のように変形・発光させる」  
Unity用カスタムシェーダーです。

VRChatでの安定動作を前提に設計されており、  
**ボーン不要・メッシュ形状非依存**で使用できます。

---

## 📌 このリポジトリについて（重要）

⚠ **このGitHubリポジトリでは、シェーダー本体の配布は行っていません。**

本リポジトリは  
**シェーダーの仕様説明・挙動紹介・公開方針（措置）を明示するための参照用リポジトリ**です。  
シェーダー本体は **BOOTH にてのみ配布**しています。

👉 **正規配布先：BOOTH**  
🔗 **[BOOTH – O-TYAN Shop](https://o-tyan64.booth.pm/items/7760459)**

---

## ✨ Features

- 🐙 **Procedural Tentacle Deformation**
  - メッシュ全体がくねくねと生き物のように変形
  - ボーン・アニメーション不要

- 🧠 **VRChat Stable Vertex Deform**
  - `unity_ObjectToWorld` 基準の安定変形
  - ワールド移動時の破綻を抑制

- 🩸 **Flesh Gradient Shading**
  - 根元 → 先端で変化する肉質カラー
  - 内部の深みを表現する疑似ディープシェーディング

- 💧 **Slime Rim & Wet Look**
  - 濡れた質感のリムライト
  - スライム的な発光表現

- 🔥 **Berserk Mode**
  - 脈動する暴走表現
  - エモート・演出用途向け

- 🎨 **MatCap Support**
  - 追加質感表現用MatCap対応

---

## 🎮 Usage（使用イメージ）

1. Unityでマテリアルを作成
2. 本シェーダーを指定
3. 任意のメッシュに適用
4. Inspector から各種パラメータを調整

※ 本リポジトリにはシェーダーファイル自体は含まれていません。

---

## ⚙ Main Parameters

### Host / Motion
| Parameter | Description |
|---------|-------------|
| Host Intensity | 変形の有効度 |
| Deform Amplitude | 変形の強さ |
| Deform Speed | うねりの速度 |
| Deform Frequency | うねりの細かさ |

### Flesh / Slime
- Base Flesh Color
- Tip Flesh Color
- Inner Darkness
- Slime Rim Color
- Wet Strength

### Berserk
- Berserk Level
- Berserk Color
- Pulse Speed

### MatCap
- MatCap Texture
- MatCap Strength

---

## 🧪 Environment

- Unity 2022 LTS
- Built-in Render Pipeline
- VRChat SDK対応想定

※ URP / HDRP 未対応

---

## ⚠ Important Notice / 利用条件・措置

This repository contains a **reference / notice only**.  
**Shader source code is NOT distributed here.**

### ✔ 許可されていること
- 本リポジトリの閲覧
- 仕様・挙動の確認
- 学習・参考目的での参照

### ❌ 禁止されていること
- BOOTH以外からのシェーダー入手
- 改変・非改変を問わない再配布
- 無断転載・再アップロード・転売
- 販売物（Booth / Gumroad / Unity Asset Store 等）への組み込み
- 再配布を目的とした解析・リバースエンジニアリング

**All Rights Reserved.**

---

## 🛒 Official Distribution / 正規配布先

シェーダー完全版（本体・調整済み・サポート付き）は  
以下の BOOTH ページにて配布しています。

👉 **[BOOTH – O-TYAN Shop](https://o-tyan64.booth.pm/items/7760459)**

- VRChat検証済み
- 調整済みプリセット
- サポート付き

---

## 👤 Author

**O-TYAN64**  
Unity / VR / Shader / Tool Developer  

GitHub: https://github.com/O-TYAN64

---

## 💬 Notes

This repository serves as a **public reference and notice**  
to clearly define the official distribution route and usage rules.

If you enjoy this shader, please consider supporting development via the full version.
