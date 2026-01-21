# 概要
パワポ等で載せる時用のEmfrpのTokenベースSyntax-Highlight。

プロジェクトディレクトリでF5を押すと.mfrpのファイルがハイライトされます。

- Tokenを追加したい -> `syntaxes/emfrp.tmLanguage.json`にルールを追加
- 色を変えたい -> Dev Hostの`settings.json`から追加（sampleディレクトリ参照）。現在のトークンのIDは、コマンドパレットから「Inspect Editor Tokens and Scopes」を選択した後、対応するトークンを選択することで確認可能
