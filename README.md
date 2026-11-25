# Japan-Ready Japanese

Netlifyで公開している静的サイト（index.html 1枚）。
予約リンク・Instagram・先着枠の数は index.html 内の `CONFIG` で変更する。

## 更新の流れ
1. `main` から作業用ブランチを切る（例：`update/pricing`）
2. Claudeが編集し、プルリクエストを出す（`main` に直接pushしない）
3. NetlifyのDeploy Previewで確認する
4. TahaがMergeする → Netlifyが `main` を自動で公開

詳しい編集ルールは `CLAUDE.md` を参照。
