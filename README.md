# CIデモ環境 構築手順書

この手順書ではJenkins、Ansible、Serverspec、GitLabを利用したCI(Continuous Integration)デモ環境を構築する手順をまとめています。

本書の手順に従ってセットアップすることで、アプリケーションのデプロイやシステムの状態の確認、管理を行うためのJenkins、Jenkinsから指示を受けてアプリケーションデプロイメントを実際に処理するAnsible、そしてAnsibleが実行する処理を記述したスクリプトであるAnsible Playbookを管理するGitlab環境を構築することができます。

手順書で使っているソースファイルは、リポジトリーにアップロードされた次のファイルを利用してください。

- ci-demo-src.zip
- spec-demo-master.zip
