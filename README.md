# 石口秀一 Wedding Photography

ウェディングフォトグラファー 石口秀一のランディングページ。

## サイト

https://kazu-wedding.netlify.app/

## 構成

```
index.html   # メインページ（CSS・JS含む）
photo/       # 使用写真
```

## 開発・デプロイ

編集後、以下を実行するだけでNetlifyに自動反映される。

```bash
git add ファイル名
git commit -m "変更内容"
git push
```

## Netlify × GitHub 自動デプロイ設定手順

1. [app.netlify.com](https://app.netlify.com) でサイトを開く
2. 左サイドバー **Deploys** → **Deploy settings**
3. **Build & deploy** → **Continuous deployment** → **Link repository**
4. **Link to an existing repository...** を選択
5. GitHubの連携画面で `kazu-wedding` リポジトリを選択
6. 設定確認画面：Branch = `main`、Base directory = 空欄のまま
7. **Deploy kazu-wedding** をクリック

完了後、Project overview に「Deploys from GitHub.」と表示されれば設定完了。
