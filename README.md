# dockerの学習用
とりあえず最小構成でdockerコンテナ上にgo言語の環境を作る  
ブログ記事読んでなんとなくなにやってるか把握できた  

Dockerfileに使用するdokcerコンテナやコンテナ内で使うツールを記述する  
ubuntuの環境構築時によく使うツールをinstall.shに書いてgithubとかに置いておいて、ubuntuインストールしたときにcloneして実行して環境構築楽にするのと同じイメージっぽい。

docker-composeではdockerのビルドやコンテナ軌道のをオプション等をまとめて記述できる。  
dockerコマンドを個別に打ち込むとミスるので基本的にdocker-composeに書いてdocker-compose upするのが良さそう。  

ディレクトリの構成どうすればいいかはよく分からん（ブログ書いている人によってまちまち）  
業務で使う場合は現場の書き方に合わせればいいか。  

## 動かし方
```> docker-compose up -d```  
```> docker-compose exec go sh```  
```> go run main.go```  

## 参考(感謝します)
https://www.engilaboo.com/go-docker/  
https://knowledge.sakura.ad.jp/13265/

