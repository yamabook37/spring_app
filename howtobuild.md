# Gradleタブから docker>composeUp でコンテナ立ち上げ
pidを消す必要があるかも
## javaのプロセスを削除
$ ps -ef | grep java
## dockerのプロセスを削除
$ docker ps
$ kill -9 (pid))
