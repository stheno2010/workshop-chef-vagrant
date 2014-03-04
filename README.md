workshop-chef-vagrant
=====================

Chef,Vagrant,Knife,Berkshelfを用いて、Chef/Vagrant入門。


## ファイルの説明
    - Vagrantfile
    　　　Vagrant起動時に読み込まれるファイル。
    　　　プロビジョニングの設定もここに記載する。
    - Berksfile
    　　　Berkshelfの設定ファイル。
    　　　Chefの依存関係解決ツール。
    　　　JavaのMAVENやIVYにあたる。
    - cookbooks/rbenv/recipes/default.rb
    　　　rbenvをインストールするためのレシピ。
    　　　レシピに記載されたコマンドは、当然ながらゲストOS上で実行できる。
    - cookbooks/rbenv/templates/default/rbenv.sh.erb
    　　　rbenvインストール時のシェル。
    - cookbooks/vim/recipes/default.rb
    　　　Vimをインストールするためのレシピ。
