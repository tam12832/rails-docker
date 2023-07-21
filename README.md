# README
  
使い方
  
このアプリケーションを動かす場合は、まずはリポジトリを手元にクローンしてください。  
\$ git clone https://github.com/tam12832/rails-docker.git <任意のディレクトリ名>
  
  
その後、リポジトリのルートディレクトリに移動し、  
次のコマンドを実行してDockerfileよりコンテナを作成、起動します。  
\$ docker-compose up
  
  
※Railsのセットアップに必要な以下の環境構築コマンドは、上記コマンド実行時に自動で実行される為、  
ユーザからの個別で入力は不要です。  
\$ bundle install  
\$ rails db:create  
\$ rails db:migrate  
\$ rails server  
  
  
次に、ブラウザからWebアプリケーションにアクセスするため、アドレスバーに  
http://localhost:3000/  
を入力し、アクセスします。
