# 概要
マージが完了していないissueを探す。
## 要素
* Issue Master
## ユースケース
* 鍵閉め中/鍵あけ中に、未反映のissueを探す。
## 関連データ
### filter
* is:issue
  - issueのみを検索対象とする。
* is:open
  - 完了していないissueを検索対象とする。
## 操作
### 鍵閉め中/鍵あけ中に、未反映のissueを探す。
#### 操作詳細
1. Issue Master リポジトリを開く。
1. issueタブを選択する。
1. filterに「is:issue is:open 機種名」を指定する。 
#### 結果
* 指定の機種で open 状態の issue の一覧が得られる。
