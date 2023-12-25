# shie-Works Zenn管理

## 新しい記事を作る

[公式のドキュメント](https://zenn.dev/zenn/articles/zenn-cli-guide)

```
npx zenn new:article
```
で`articles/ランダムなslug.md`が作成される

これに記事を書く。

## プレビュー

```
npx zenn preview
```


## 画像

[GitHubリポジトリ連携で画像をアップロードする方法](https://zenn.dev/zenn/articles/deploy-github-images)

vscodeにpaste Imageをインストールすると便利

[paste Imagesの設定方法](https://zenn.dev/simiraaaa/articles/zenn-vscode-paste-image)

設定はWorkSpace側でやっちゃうのが便利

画像の貼り付けは   
<font size="5" >**「Ctrl+Alt+V」**</font> で行う

```
{
  "pasteImage.basePath": "${currentFileDir}/..",
  "pasteImage.insertPattern": "${imageSyntaxPrefix}/${imageFilePath}${imageSyntaxSuffix}",
  "pasteImage.path": "${currentFileDir}/../images"
}
```



# Zenn CLI

* [📘 How to use](https://zenn.dev/zenn/articles/zenn-cli-guide)