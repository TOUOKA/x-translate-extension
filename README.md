# X Auto Translator 🚀

A Chrome Extension that automatically translates English posts from a specific user on X (formerly Twitter) into Japanese.

特定のX（旧Twitter）ユーザーの英語投稿を自動で日本語翻訳するChrome拡張機能です。

---

## 🧩 Features / 機能

- Automatically detects posts from a specific user (e.g. @elonmusk)
- Translates English posts to Japanese using LibreTranslate API
- Toggle ON/OFF via the extension popup
- No need to click "Translate" – translations appear automatically
- Lightweight and privacy-friendly

特長：
- 特定ユーザーの投稿だけを対象
- 英語投稿をLibreTranslate APIで日本語に翻訳
- 拡張機能のON/OFFを切替可能
- ボタン不要、翻訳結果は自動表示
- 軽量でプライバシーにも配慮

---

## 📦 Installation / インストール方法

1. Clone or download this repository
2. Open `chrome://extensions/` in Chrome
3. Enable "Developer mode"
4. Click "Load unpacked" and select the folder

1. このリポジトリをクローンまたはZIPでダウンロード  
2. Chromeで `chrome://extensions/` を開く  
3. 「デベロッパーモード」をON  
4. 「パッケージ化されていない拡張機能を読み込む」をクリックし、フォルダを選択

---

## 🔧 Configuration / 設定

To change the target user (e.g., from `@elonmusk` to another), edit the following line in `content.js`:

```js
const targetUser = "@◯◯◯◯"; // ← change here
