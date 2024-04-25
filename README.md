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

## 新しいパソコンで動かす

[GitHub](https://github.com/shie-works/shie-works-zenn-docs)からcloneする

```bash
~/docker/ git clone git@github.com:shie-works/shie-works-zenn-docs.git
```
cloneが完了したら、  
`shie-works-zenn-docs`というフォルダができているので、
そこに移動

```bash
~/docker/ cd shie-works-zenn-docs
```

npm インストールする
```bash
~/docker/shie-works-zenn-docs/ npm install
```

これで、執筆環境ができたので、  
次は下記「画像を楽に配置する方法」に記載している手順を行う

## 画像を楽に配置する方法

[GitHubリポジトリ連携で画像をアップロードする方法](https://zenn.dev/zenn/articles/deploy-github-images)

vscodeにpaste Imageをインストールすると便利
設定はWorkSpace側でやっちゃうのが便利

上部メニュー＞ファイル＞ユーザー設定　で設定画面が開く

設定画面上での作業
 * ワークスペースタブを開く
 * 画面一番右上の「設定(JSON)を開く」をクリックして`setting.json`を開く
 * 以下のコードを張り付け

```
{
  "pasteImage.basePath": "${currentFileDir}/..",
  "pasteImage.insertPattern": "${imageSyntaxPrefix}/${imageFilePath}${imageSyntaxSuffix}",
  "pasteImage.path": "${currentFileDir}/../images"
}
```



画像の貼り付けは   
<font size="5" >**「Ctrl+Alt+V」**</font> で行う


[paste Imagesの設定方法](https://zenn.dev/simiraaaa/articles/zenn-vscode-paste-image)



# Zenn CLI

* [📘 How to use](https://zenn.dev/zenn/articles/zenn-cli-guide)
* 