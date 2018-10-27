# GitHub Wikis 入門
これはGitHubでソースコード管理しかしたことがない自分を含めた初心者用のメモになります(英語の勉強も含めて)。  
かなりくだいてメモしていますが、もしよければご覧ください(時間が空いたときにちょこちょこ書きます)
<br>
<br>
※ これは`2018/10/27`時点のものです

## 1. GitHub Wikisとは
`GitHub Wikis`は下記のような場合に使われることがあるといいます
- どのような経緯、原則などより詳細な内容を伝えたい
- `README.md`より詳細な内容を伝えたい  
> GitHub Wikis are a place in your repository where you can share long-form content about your project, such as how to use it, how it's been designed, manifestos on its core principles, and so on. Whereas a README is intended to quickly orient readers as to what your project can do, wikis can be used to provide additional documentation.
<br>

では README.md はどのように使うのかというと

- そのリポジトリの機能をインストールすることでできるようになること
- インストールの仕方、使い方  
- 分りやすいような画像(gifは見ていて使うイメージが湧く)  
を簡潔にまとめたもので`クイックスタートガイド`的なやつです。
<br>
一番の違いは

>一番違うのはREADME.mdは同一リポジトリだけど、Wikiは別リポジトリという点だと思う
両方管理するとしたら、例えばこんな観点で分けると良いんじゃあないかな  
[readmeとwikiの違い](https://qiita.com/suzuki-hoge/items/1d6022cca177e2d96bb5#readme%E3%81%A8wiki%E3%81%AE%E9%81%95%E3%81%84)  

下記の比較表はとても分りやすいです  

|  | README.md | Wiki |
|:-----------:|:------------:|:------------|
| 更新頻度 | 頻繁 | ほとんど無い |
| PullRequestに | 含めたい | 含めなくて良い |
| 管理者 | 開発者 | 例えばPOやディレクター |
| 内容 | 開発者用 | システム利用者用 |

## 2. GitHubWikis を使ってみる
1. レポジトリを作成する
    1. 右上の`+` => new repository
    2. Repository name（リポジトリの名前）: 任意の名前を入力(-,_ を使える)
    3. 問題なければ `Create Repository`をクリック

2. GitHubWikis の編集権限を変更する(現在のままではだれでも変更できてしまう)
    1. `1-iii`をクリックした後の画面の `Settings` をクリック
    2. 
# 3. GitHub Wikis の注意点



追記(2018/10/2)[GitHubカンニング・ペーパー](https://github.com/tiimgreen/github-cheat-sheet/blob/master/README.ja.md#github)



### 参考サイト
>- [Github Help(英語)](https://help.github.com/categories/wiki/)
>- [GitHub Wikiの編集ノウハウ](https://github.com/doc-wiki-jp/wiki/wiki/GitHub-Wiki%E3%81%AE%E7%B7%A8%E9%9B%86%E3%83%8E%E3%82%A6%E3%83%8F%E3%82%A6)
>- [[github wiki] Wikiを管理する](https://qiita.com/suzuki-hoge/items/1d6022cca177e2d96bb5#github-wiki-wiki%E3%82%92%E7%AE%A1%E7%90%86%E3%81%99%E3%82%8B)
>- [GitHubを中心とした開発プロセス ドキュメント管理](https://qiita.com/suzuki-hoge/items/1d6022cca177e2d96bb5#github-wiki-wiki%E3%82%92%E7%AE%A1%E7%90%86%E3%81%99%E3%82%8B)

https://qiita.com/suzuki-hoge/items/a6e3bdc2cc1cf4e98ea1