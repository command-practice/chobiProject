# 前提条件
1. gitをインストール ([git]コマンドを使用できるように)　[Git](https://git-scm.com/downloads)
2. Github Desktopをインストール (GUIを使用できるように)　[Github DeskTop](https://github.com/apps/desktop?ref_cta=download+desktop&ref_loc=installing+github+desktop&ref_page=docs)
  
## リポジトリの作成の仕方
1. 「Repositories」から「New repository」をクリック。  
2. repositoryの「名前」と「公開設定 (public・private)」を設定して「Create repository」をクリック。  
3. 自PCからアップロードしたいプロジェクトをエディター上で開きエディター上でターミナルを起動する。  
   ``` md
   git init
   ```
   と打ちEnterを押す。  
5. 「git add .」と打ちEnterを押す。  
6. Create repositoryの後の画面の生成されたURL```「https://github.com/リポジトリー名.git」```をコピーしてくる。  
7. 「git remote add origin [生成されたURL]」と打ちEnterを押す。  
8. 「git commit -m "first commit"」と打ちEnterを押す。  
9. 「git push origin main」と打ちEnterを押す。  
10. Githubに戻り作成したリポジトリ画面でリロードする。  
