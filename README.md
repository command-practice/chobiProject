# 前提条件
1. gitをインストール ([git]コマンドを使用できるように)　[Git](https://git-scm.com/downloads)
2. Github Desktopをインストール (GUIを使用できるように)　[Github DeskTop](https://github.com/apps/desktop?ref_cta=download+desktop&ref_loc=installing+github+desktop&ref_page=docs)
  
## リポジトリの作成の仕方
1. 「Repositories」から「New repository」をクリック。  
2. repositoryの「名前」と「公開設定 (public・private)」を設定して「Create repository」をクリック。  
3. 自PCからアップロードしたいプロジェクトをエディター上で開きエディター上でターミナルを起動する。  
4. ターミナルで以下を貼り付け実行
   ``` md
   git init
   ```  
5. ターミナルで以下を貼り付け実行
   ``` md
   git add .
   ```
6. ターミナルで以下をコピーし生成されたURLだけgithubからコピー・貼り付けて実行
   ``` md
   git remote add origin [生成されたURL]
   ```
7. ターミナルで以下を貼り付けて実行
   ``` md
   git commit -m "first commit"
   ```
8. ターミナルで以下を貼り付けて実行
   ``` md
   git push origin main
   ```
9. Githubに戻り作成したリポジトリ画面でリロードする。  
