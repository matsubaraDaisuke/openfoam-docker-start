# openfoam-docker-start
Docker上でfundation版OpenFOAMの開発環境を構築するためのリポジトリ

# 環境構築
``` terminal
$ git clone git@github.com:matsubaraDaisuke/openfoam-docker-start.git
$ docker-compose up --build
$ docker-compose run openfoam /bin/sh
```

# 使い方
of-developディレクトリが`OpenFOAM`の`$WM_PROJECT_USER_DIR`にマウントされます．

of-developディレクトリの中で開発を行ったり，計算のインプットファイルを作成して，他者に共有することができます．

Qiita記事も参考にしてください．
https://qiita.com/matsubaradaisuke/items/5330a66801142d6afd6a
