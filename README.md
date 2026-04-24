# PracticeGithub
このリポジトリは鶴田プロジェクトのメンバーがGithubに慣れるために
使用するものとなります。

この下にGithubを使用するときにやるべきことを書いていきます。

# Githubのリポジトリを立てた時にまずやること

## gitとGithubを関連づけ、Github上の進捗をローカルに持ってくる

まず、gitとGithubを関連づける必要があります。
その時に同時にGithub(リモート)上の進捗をローカルに持っていくことができます。
<br>
以下のコマンドを使用するディレクトリ上で叩きます。
git clone <Githubのurl> .
<br>
今回は
git clone.  https://github.com/TsurutaProject/PracticeGithub.git .<br>
と叩きます。

すると、gitとGithubを関連つけると同時に、Github上の進捗をローカルに持ってくることが可能です。

## branchの作成と移動
まず何も考えずに以下のコマンドを叩いてください。

git branch <br>
すると<br>
*main<br>
という表示が出るかと思います。
この場合、「今はmainブランチにいる」ということを表しています。
基本的にGithubを使うときの共同開発はmainブランチはいじらないということになっています。
そのため、以下のコマンドを叩き、ブランチを作成し移動する必要性があります。

git checkout -b feature-<自分が使用するbranch><br>
<自分が使用するbranch>の名前はアルファベットを使用し、自分の名前を入れてもらいたいです。
ex) git checkout -b feature-norimaki <br>
そうするとnorimakiというブランチを作成し、移動することができます。




