# aws-shellのDockerイメージ

[aws-shell](https://github.com/awslabs/aws-shell)を起動するDockerイメージ

## 起動

Docker Compose を利用して起動する

プロファイルを利用したい場合、--profile(又は、-p)オプションを指定する。

```
docker-compose run --rm aws-shell <--profile プロファイル名>
```

## イメージ構築

普通にDockerでイメージを構築

```
cd aws-shell
docker build -t aws-shell:latest .
```
