# docker-win-python
DockerでPython実行環境を構築（Windows）

## 環境
- Windows 11 Pro 22H2
- Ranchar Desktop：1.8.1

## コンテナ起動
ダウンロードしたリポジトリフォルダに移動して実行
~~~
>  docker-compose up -d --build
~~~


## コンテナ接続
~~~powershell
#コンテナID取得
> docker ps
#コンテナに接続
> docker exec -it [コンテナID] bash
~~~

## コンテナでPython実行
~~~console
$ python run.py
~~~

## 参考
