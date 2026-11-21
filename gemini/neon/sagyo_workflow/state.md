# 作業状態

## 目的
この ChatGPT 会話の可視部分を、GitHub 上で読みやすい会話記録として保存する。作業の判断・手順・復旧方法・定型化のヒントも別途記録する。

## 保存先
- リポジトリ: [nozomiidev/ImportantChatAIkaiwa](https://github.com/nozomiidev/ImportantChatAIkaiwa)
- ブランチ: `main`
- 対象ディレクトリ: `gemini/neon/`
- 作業ログ: `gemini/neon/sagyo_workflow/`
- 基点コミット: `9ea239f81e2ce815a9fc30fd8351829bf7f6844c`（開始時点の `main`）
- 最新チェックポイント: `3ad27e12568468e3732c319c367e63587a2dd04f`

## 進捗スナップショット
- [x] リポジトリ権限、既定ブランチ、保存先ディレクトリを確認。
- [x] 保存先をブランチではなく `gemini/neon/` ディレクトリと特定。作業ブランチは `main`。
- [x] `conversation.md` の初版を作成。
- [x] `README.md` に記録の読み方と構成を記載。
- [x] `sagyo_workflow/README.md`、`progress.md`、`decisions.md`、`conversation-template.md` を作成。
- [ ] 会話記録に、作業中の可視進捗メッセージを最終スナップショットとして反映。
- [ ] GitHub 上の一覧・内容・最新コミットを読み直して検証。
- [ ] 検証結果を進捗に追記し、この状態ファイルを完了にする。

## 復旧手順
環境が切断・初期化された場合は、このファイルを最初に読み、続いて `sagyo_workflow/progress.md` と `sagyo_workflow/decisions.md` を読む。GitHub の `main` で最新のコミットとファイル内容を確認し、既存ファイルを重複作成しない。未完了の項目だけを再開し、各まとまりの完了時に進捗と状態を更新してコミットする。

## 記録範囲
会話記録には、Gemini を開く依頼から本記録の確定までに画面上で確認できるユーザー／アシスタントの文章を収録する。非表示の指示や内部ツール出力は含めず、ブラウザー操作の観察は作業ログに残す。Gemini ではサインインもプロンプト送信もしていない。
