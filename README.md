# JupyterLab
JupyterLab用のサンプルです。（自分用）



①ディレクトリ内でdockerのbuildを行う。

```
docker compose up -d --build
```

②コンテナが正常に起動したか確認

```
docker container ls
```

③中に入るには下記コマンド

```
 docker compose exec -it jupyterlab bash
```

中に入り、URLを確認し、入ればJupyterLab
