## 環境構築用
・laravel10  
・php8  
・mysql8  
・apache2  
※参考資料　https://qiita.com/kitajii/items/40ce2202f6623ad58dcf

## 手順
laravelの画面を表示するまで  
1 ```docker compose build```  
2 ```docker compose up```  
3 ブラウザでlocalhostに接続  

## laravelのバージョンを変更
現状はlaravel10だが、変更する場合はsrc配下を全て削除し以下コマンドを実行  
```composer create-project "laravel/laravel={任意のバージョン}.*" ./```  
※srcディレクトリにはlaravelしか入っていない。
