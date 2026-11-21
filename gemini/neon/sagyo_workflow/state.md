# 作業状態

## 目的
この ChatGPT 会話の可視部分を、GitHub 上で読みやすい会話記録として保存する。作業の判断・手順・復旧方法・定型化のヒントも別途記録する。

## 保存先
- リポジトリ: [nozomiidev/ImportantChatAIkaiwa](https://github.com/nozomiidev/ImportantChatAIkaiwa)
- ブランチ: `main`
- 対象ディレクトリ: `gemini/neon/`
- 作業ログ: `gemini/neon/sagyo_workflow/`
- 基点コミット: `9ea239f81e2ce815a9fc30fd8351829bf7f6844c`（開始時点の `main`）

## 進捗スナップショット
- [x] リポジトリの既定ブランチ、権限、既存の `gemini/neon/` を確認。
- [x] 保存先をブランチではなくディレクトリとして特定。ブランチ名は `main`。
- [ ] 会話記録 `conversation.md` を作成。
- [ ] `README.md` に記録の読み方と構成を記載。
- [ ] `sagyo_workflow/` に作業記録、判断、復旧手順、定型化のヒントを作成。
- [ ] 作成後に保存内容と GitHub 上のコミットを確認し、この状態ファイルを最終化。

## 復旧手順
環境が切断・初期化された場合は、このファイルを最初に読み、続いて同じディレクトリの `sagyo_workflow/progress.md` と `sagyo_workflow/decisions.md` を読む。GitHub の `main` で最新のコミットとファイル内容を確認し、既存ファイルを重複作成しない。未完了の項目だけを再開し、各まとまりの完了時に進捗と状態を更新してコミットする。

## 記録範囲
会話記録には、保存作業の依頼時点までに画面上でユーザーとアシスタントが交わした文章を収録する。ブラウザー操作の観察や実施内容は会話本文と混ぜず、作業記録に残す。認証や Gemini へのプロンプト送信は行っていない。
