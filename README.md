# openfoam-docker-start
Docker上でfundation版OpenFOAMの開発環境を構築するためのリポジトリ

# 環境構築
``` terminal
$ docker-compose up --build
$ docker-compose run openfoam /bin/sh
```

# 使い方
of-developディレクトリがOpenFOAMの$WM_PROJECT_USER_DIRにマウントされます．
of-developディレクトリの中で開発を行ったり，計算のインプットファイルを作成して，他者に共有することができます．
