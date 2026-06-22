# nebu-tools

公開用の小さなWebツール集。各ツールは単一HTMLファイルで動作し、ブラウザだけで使えます（ビルド不要）。

データはすべて各ツール内の `localStorage` に保存され、外部サーバーには送信されません。

## ツール一覧

| ツール | 説明 |
|---|---|
| [mangaflow-timer](mangaflow-timer/) | 作業タイマー（タスク別の時間記録・週/月/年の統計・CSV出力） |

## 構成

```
nebu-tools/
  ├── README.md
  └── <tool-name>/
      └── index.html
```

ツールを追加する場合は `<tool-name>/index.html` の形でフォルダを作る。GitHub Pages を使う場合、各ツールは `https://<user>.github.io/nebu-tools/<tool-name>/` で公開される。
