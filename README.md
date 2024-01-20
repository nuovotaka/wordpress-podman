MacOS(Intel)で作成しました。

[Podman Desktop](https://podman-desktop.io/) で Wordpress の開発環境を作成

wordpress-pod.yml をご自身の好きなワークフォルダにクローンして使ってください。

Pods タブの”Play Kubernets YAML”にて読み込む

```
localhost:9000にアクセス
```

### WordPress の初期設定画面が表示

表示された後は、画面の指示に従って操作を行うこと。
これはあくまでも開発用です。

#### docker

docker で動作していたのものを Podman に対応しました。
データベースは madiadb を使用しています。
