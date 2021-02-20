## npm   
・正式名称はNode Package Manager。node.jsのパッケージマネジャー   
・-gのオプションをつけるとコンピューター内すべてのパッケージを示す。　☆超重要   
・-gが無い場合、現在操作中のディレクトリ内（フォルダ内）での操作を示す。   

## save-devオプションの意味
・パッケージの依存関係を環境別に整理するための意味合いとして利用される。   
・反対のオプションとして、--productionというオプションが存在する。   
・-gをつけないとローカルインストールだが、--save-devのオプションをつけてもローカルインストールになる。   
　--save-devのオプションをつけた場合は自動で package.jsonの devDependencies に追記される。   
　そして dependencies には追記されない。   
・パッケージ間の依存関係の整理はpackage.jsonという設定ファイルの「devDependencies（save-devオプションにて管理される設定）」   
　「Dependencies（--productionオプションにて管理される設定）」に格納される。
 
 ![image](https://user-images.githubusercontent.com/18514297/108577497-a65d7a80-7364-11eb-8a0d-04443d3a0649.png)
