# 概要
特定の機種に対する修正を許可する。
## 要素
* BASELINEリポジトリ
* 各モジュールリポジトリ
## ユースケース
* 指定された機種の鍵あけを行う。
## 関連データ
### Pull Request
#### status
* merge-status
  - success : マージ許可
## 操作
### 指定された機種の鍵あけを行う。
#### 詳細操作
1. BASELINEリポジトリの指定された機種のissueを表示する。
1. 「reopen issue」ボタンを押す。
#### 結果
* 指定された機種に結び付くすべての Pull Request の merge-status が success （マージ許可）となる。  
