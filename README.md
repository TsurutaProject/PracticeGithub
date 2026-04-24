# PracticeGithub
このリポジトリは鶴田プロジェクトのメンバーがGithubに慣れるために
使用するものとなります。

この下にGithubを使用するときにやるべきことを書いていきます。

# Githubのリポジトリを立てた時にまずやること

## gitとGithubを関連づける
まず、git(ローカル)側の設定をする必要があります。
gitについての説明は知っていると思うので割愛します。

git init
をした後、git(ローカル)とGithub(リモート)を関連づける必要性があります。

そのためには使用するディレクトリをカレントディレクトリにして以下のコマンドをターミナル上で叩きます。

git remote add origin <Githubのurl>.git
今回は
git remote add origin https://github.com/TsurutaProject/PracticeGithub.git

を入力します。
そうすると、gitとGithubを関連づけることができます。