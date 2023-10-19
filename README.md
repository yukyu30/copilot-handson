# GitHub CopilotWorkshop [Japanese]

GitHub Copilot のワークショップです

## ワークショップのドキュメントの更新方法 (Contributor 向けの情報)

本ワークショップのドキュメントは Markdown 形式のファイル (`workshop.md`) を [claat (Google Codelabs command line tool)](https://github.com/googlecodelabs/tools/tree/main/claat) でレンダリングして作成しています。

以下の手順でドキュメントを更新します。

1. 以下ドキュメントを参考にして claat をセットアップする
    - https://zenn.dev/nakazax/articles/18506708b5eea9
2. `workshop.md` を更新する
3. ターミナルで `claat export workshop.md` を実行し `docs/` ディレクトリ配下のファイル群が更新されることを確認する
4. ターミナルで `claat serve docs/` を実行しレンダリング結果を確認する
