# Git操作早見表

## 基本的な操作手順

### 変更を反映したいとき

1. ファイルをステージングエリアに追加

    ```bash
    git add ファイル名
    ```

2. ファイルをコミット

    > [!WARNING]
    > コミットメッセージはダブルクオーテーションで囲ってください

    ```bash
    git commit -m コミットメッセージ
    ```

3. ファイルをプッシュ

    ```bash
    git push origin <branch-name>
    ```

### 変更を取り込みたいとき

> [!WARNING]
> 現在いるブランチを確認してからやること！

```bash
git pull
```

OR

```bash
git pull origin <branch-name>
```

### 変更は取り込みたくないけど、リモートの変更の情報がほしいとき

```
git fetch
```


### ブランチを変えたいとき

```bash
git switch <branch-name>
```

### 現在のブランチ一覧を確認したいとき

```bash
git branch
```

### ブランチを新しく作りたいとき（作った後に移動するまで）

```bash
git switch -c <branch-name>
```

