# RuckStudy - Git

Gitを学ぶための練習用リポジトリ

## 参考動画

[【Git入門講座 合併版】この動画1本でGitとGitHubの基礎をゼロからマスター！【初心者向け】](https://youtu.be/WHwuNP4kalU?si=s2RaKO-2KUK4_pzy)

### 基本操作

```bash
# ローカル基本操作①初期化（19:12〜）
git init

# ローカル基本操作②記録（20:11〜）
git add <ファイル名>
git commit -m "コミットメッセージ"

# ローカル基本操作③状況確認（23:26）
git diff <ファイル名>
git diff -staged
git status

# ローカル基本操作④履歴の確認（25:22〜）
git log

# ローカル基本操作⑤元に戻す（26:50〜）
git restore
git restore -stage <ファイル名>
```

### ブランチ

```bash
# ブランチ①作成（33:27〜）
git branch <新しいブランチ名>

# ブランチ②一覧を表示する（34:09〜）
git branch
git branch -a

# ブランチ③ブランチの一覧を表示（35:06〜）
git switch <ブランチ名>
git switch -c <新しいブランチ名>

git checkout <ブランチ名>
git checkout -b <新しいブランチ名>

# ブランチ④変更をマージ
git merge <取り込みたいブランチ名>
```

### Github

```bash
# GitHub①初期設定（42:17〜）

# GitHub②リポジトリ追加（43:42〜）
git remote add origin <リモートURL>
git push origin <プッシュ先のブランチ名>

# GitHub③プル（45:15〜）
git pull origin <取得したいブランチ名>
git pull

# GitHub④フェッチ（47:02〜）
git fetch origin
```

## 参考

- [良いコミットメッセージのルールメモ](https://zenn.dev/shotaro/articles/2022-04-20-0000)
