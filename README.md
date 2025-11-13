# 丸バツゲーム PWA

Progressive Web App（PWA）対応の3x3丸バツゲーム（Tic-Tac-Toe）です。

## 特徴

- 📱 PWA対応でオフラインでも動作
- 🎮 シンプルな3x3の丸バツゲーム
- 🎨 モダンでレスポンシブなデザイン
- ⚡ 高速な動作
- 📲 ホーム画面に追加可能

## 遊び方

1. プレイヤー⭕とプレイヤー❌が交互にマスをクリックします
2. 縦、横、斜めのいずれかに同じマークを3つ並べると勝利です
3. すべてのマスが埋まっても勝負がつかない場合は引き分けです
4. 「リセット」ボタンでゲームをリセットできます

## 技術スタック

- HTML5
- CSS3
- Vanilla JavaScript
- Service Worker（PWA）
- Web App Manifest

## GitHub Pagesでの公開

このプロジェクトはGitHub Pagesで公開されています。
`main`ブランチにプッシュすると自動的にデプロイされます。

## ローカルでの実行

1. リポジトリをクローン
2. `index.html`をブラウザで開く

または、簡易的なHTTPサーバーで実行：

```bash
# Pythonを使用する場合
python -m http.server 8000

# Node.jsのhttp-serverを使用する場合
npx http-server
```

## PWAの機能

- オフライン対応
- ホーム画面へのインストール
- アプリライクな体験
