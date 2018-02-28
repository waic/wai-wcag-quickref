# How to Meet WCAG 2 (クイックリファレンス)

[ウェブアクセシビリティ基盤委員会 (WAIC) 翻訳ワーキンググループ (WG4)](http://waic.jp/committee/wg4/) が管理する、[How to Meet WCAG 2 (クイックリファレンス)](http://waic.jp/docs/WCAG20/quickref/)のレポジトリです。

GitHub 上でビルドされたファイルは

- https://waic.github.io/wai-wcag-quickref/

から閲覧可能です。


## ローカルでのビルド方法
rubyで動作するjekyllでビルドします。bundleが必要でしょう。
動作環境を整えた上でローカルのリポジトリのあるフォルダーに移動して、

    $ bundle exec jekyll serve

とすれば、コンソールにServer addressが表示されるので、そのURLをブラウザーに入力すれば表示されます。


## 主要なディレクトリー・ファイル構成
```
- _data/wcag2.json      # 達成方法集のタイトル
- _include/             # サイトのパーツ構成ファイル
- _help/                # ヘッダー部分のヘルプ
```


## Pull Request 等について

Pull Request は、ブランチ `gh-pages` にお願いします。また、issue を立ててもらっても構いません。どちらの方法でも歓迎します。
メールで込み入った質問等をしたい場合は、[WAIC のお問い合わせページ](http://waic.jp/contact/)にお願いします。
