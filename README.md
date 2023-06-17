# python-toukei-study
参考書：あたらしい Python で学ぶ統計学の教科書（第二版）
勉強用ディレクトリ

# ローカル環境構築
## Python パッケージ管理ツール「Rye」[^1]を使用

### 使い方[^2]

1. rye をインストール

    $ curl -sSf https://rye-up.com/get | bash

    $ echo 'source "$HOME/.rye/env"' >> ~/.zshrc

    $ source ~/.zshrc

2. プロジェクト「python_toukei_study」の作成

    $ rye init python_toukei_study

3. Python のバージョン指定（今回は 3.10 を使用）

    $ rye pin 3.10

[^1]: https://rye-up.com/

[^2]: 詳細はブログに執筆予定です
