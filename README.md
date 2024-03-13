# practice-github

test変更1
test変更2
レビュー機能？を試したい
dot変更1
変更2

# 03
03のテキストです。
まとめです。
さらにまとめ

# 11 直近のコミットメッセージを修正
```
git commit --amend -m "メッセージ"
```
まとめです。
さらにまとめ

# 12 新しくコミットを作るまでもないとき
```
git commit --amend --no-edit
```
- 1つ前以上のコミットを修正したい場合は基本しないほうがいい（混乱をふせぐため）
まとめです。
さらにまとめ

# 13 過去の内容を確認する
```
git checkout ハッシュ（過去に戻る）
git switch - // 元の状態に戻る（未来に戻る）
```
まとめです。
さらにまとめ

# 14 
other.md
まとめです。
さらにまとめ

# 15
```
git commit -a -m "メッセージ"
git commit -am "メッセージ"
```
- untracked file は対応しない `-a`
まとめです。
さらにまとめ

# 17
- `git reset` 基本的に消えてしまうので、みんなと共有していないコミットのみにするべき
- `--hard`: 指定したところまで戻って、その時点のコードに戻る（それまでの変更は全てなくなる）
- `--soft`: 指定したところまで戻るけど、今いるところのワーキングディレクトリ、ステージングエリアのものは消えない
- `--mixed`: 指定したところまで戻る、ステージングエリアかはなくなる、ワーキングディレクトリに現在の状態が残る
まとめです。
さらにまとめ