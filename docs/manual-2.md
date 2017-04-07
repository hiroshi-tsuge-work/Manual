# 概要
特定の機種に対する修正を禁止する。
## 要素
* BASELINEリポジトリ
* 各モジュールリポジトリ
## ユースケース
* 指定された機種の鍵閉めを行う。
## 関連データ
### Pull Request
#### status
* merge-status
  - pending : マージ不可
## 操作
### 指定された機種の鍵閉めを行う。
#### 詳細操作
1. BASELINEリポジトリの指定された機種のissueを表示する。
1. 「close issue」ボタンを押す。
#### 結果
* 指定された機種に結び付くすべての Pull Request の merge-status が pending（マージ不可）となる。  
（注） pending状態でも、作業ブランチ上でのソースコード修正、commit、pushは行える。
