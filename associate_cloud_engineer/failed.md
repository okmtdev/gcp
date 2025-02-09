# Udemy 講座で間違った問題

## Deployment Manager の preview フラグ

あなたが参加しているプロジェクトでは、Deployment Manager を使用してリソースをデプロイします。あなたはテンプレートに大きな変更を加えました。変更をコミットする前に、定義されている全てのリソースの依存関係が適切に満たされていることを確認する必要があります。変更後の結果を最も素早く確認するには、どうすれば良いでしょうか？

> [!TIP]
> gcloud コマンドラインツールを--preview フラグを使用して実行する。実行結果で相互に依存するリソースの状態を確認する。

> [!NOTE]
> Helpful advice for doing things better or more easily.

> [!WARNING]
> --dry-run は存在しない

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

## VM インスタンスの停止コマンド

あなたの所属する企業では複数の VM インスタンスを使用して Web アプリケーションを実行しています。あなたは gcloud コマンドツールを使用して web-app-1 という名前のインスタンスを停止する必要があります。以下のうち、どのコマンドを実行すれば良いでしょうか？

> [!TIP]
> gcloud compute instances stop web-app-1

> [!WARNING]
> gcloud compute stop web-app-1 は無効なコマンド。

## App Engine の環境ごとの作成方法

あなたのチームは App Engine アプリケーションを開発しており、開発環境でのテストを完了しました。新しいプロジェクトを本番環境として作成し、アプリケーションを実行する必要があります。どうすれば良いでしょうか？下記の手順から適切なものを２つ選択して下さい。

> [!TIP]
>
> 1. gcloud projects create コマンドを使用して新しいプロジェクトを作成する。
> 2. --project フラグに新しいプロジェクトの ID を指定し、gcloud app deploy コマンドを実行してアプリケーションを新しいプロジェクトにデプロイする。

> [!WARNING]
> gcloud app copy は無効なコマンド。

# 本で間違った問題

# 模擬試験で間違った問題
