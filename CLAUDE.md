# かず Wedding Photography LP

## プロジェクト概要

石口秀一のウェディングフォトグラファーLP。単一の `index.html` にCSS・JSをインライン記述。写真は `photo/` フォルダ参照。

- URL: https://kazu-wedding.netlify.app/
- GitHub: https://github.com/0403aoki-test/kazu-wedding
- ホスティング: Netlify（GitHub連携で自動デプロイ）

## デプロイ

```bash
git add ファイル名
git commit -m "変更内容"
git push
```

pushするだけでNetlifyに自動反映される。

## 編集ルール

### テキスト修正
- 既存のトーン（丁寧語・敬語）を維持する
- `<em>` などのHTMLタグ構造は変えない
- 日本語・英語の混在スタイルを維持する

### 写真
- 写真は `photo/` フォルダに追加する
- `index.html` の `src` 参照先だけ変える
- ファイル名は変更しない

### 変更禁止
- カラー変数（`--accent`、`--text` など）は変更しない
- フォント（Cormorant Garamond / Noto Serif JP / Noto Sans JP）は変更しない
- コンタクトフォームのHTML・JSは変更しない（Netlify Formsと連携中）
