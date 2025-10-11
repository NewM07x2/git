# git
git dev

## ブランチの一覧を見る
git branch -a

git merge branch_name

## 一時退避する
git stash push -m "コメント"

## 一時退避した内容を戻す
### 最新stashを戻す
git stash apply

### 特定の stash を戻す
git stash apply stash@{1}

## 取り出して削除する
git stash drop stash@{0}

## 全て削除
git stash clear