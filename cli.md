# gcloud CLI

## gcloud config configurations

gcloud CLI の設定を管理するコマンド

```
設定 A

- project = my-projectA
- account = xxx@example.com

設定 B

- project = my-projectB
- account = yyy@example.com
```

```
# 表示
gcloud config configurations list

# 作成
gcloud config configurations create my-config

# 有効化
gcloud config configurations activate my-config
```

## gcloud config set

gcloud CLI の設定を変更するためのコマンド

```
# 現在のデフォルトのリージョンを変更
gcloud config set compute/region us-central1

# 現在のデフォルトのゾーン設定を変更
gcloud config set conpute/zone us-central1-a
```

## gcloud compute instances create

Conpute Engine インスタンスを作成するためのコマンド

```
gcloud compute instance create my-instance --machine-type=n1-standard-2 --zone=us-central1-a
```

## gcloud compute ssh

Compute Engine インスタンスに SSH で接続するコマンド

```
gcloud compute ssh INSTANCE_NAME
```

## gcloud compute netwroks create

VPC ネットワークを作成するコマンド

```
gcloud compute networks create my-network --subnet-mode=custom
```

- subnet-mode: custome だと手動、auto だと自動

## gcloud compute networks subnets create

VPC ネットワーク内にサブネットを作成するコマンド

```
gcloud compute networks subnets create SUBNET_NAME --network=NETWORK_NAME --range=IP_RANGE
```

- IP_RANGE: サブネットに割り当てる IP アドレスの範囲を指定する。192.168.0.0/24

## gcloud compute networks subnets expand-ip-range

サブネットの IP アドレス範囲を変更するためのコマンド

```
gcloud compute networks subnets expand-ip-range SUBNET_NAME my-subnet --prefix-length=23
```

- PREFIX_LENGTH: サブネットのプレフィックス長を指定する

## gcloud container clusters

GKE のクラスタを操作するためのコマンド
