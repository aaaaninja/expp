expp
====
puppeteerの最小構成 (typescript)  
puppeteerをtypescriptで動かしていく実験場

使用法
------
動かすとpngが2枚, project root下に生成されます.

### setup (git clone直後)
```sh
# project rootに移動
cd expp
yarn
yarn run tsc
```

### 実行
```sh
node build/index.js
```

todo
----
jestとかでtestを作ってみたい......

- [Qiita - JestとPuppeteerでお手軽(Visual)レグレッションテスト](https://qiita.com/kiida/items/fae689b8a58c30c5e337)
>- https://github.com/smooth-code/jest-puppeteer/  
>Jestのテスト内でPuppeteerのpageオブジェクトが使えるようになります。またいくつかのmatcherが追加されます。

>- https://github.com/americanexpress/jest-image-snapshot/  
>スクリーンショットが一致しない場合はテストを失敗させた上でsnapshot保存先ディレクトリ(デフォルトは<PROJECT_ROOT>/snapshots)内の__diff_output__というディレクトリ内に以下のようなファイルを生成してくれます。
![実行例](https://camo.qiitausercontent.com/36233ebbb75798c050f7ceb176f2624f2f11e3a0/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e616d617a6f6e6177732e636f6d2f302f33363030332f35626262373833342d616363372d386232342d666464332d3065303437303236323338342e706e67)
