# AdmmForLasso
Alternating Direction Method of Multipliers (ADMM)をLassoへ適用するアルゴリズムを作成しました。(５セル目)
また、サンプルとしてボストンの物件価格を予測するプログラムを用意しました。(７〜８セル目)

※サンプルデータとして機械学習ライブラリ『scikit-learn』の『Bostonデータセット』を使用しました。(１〜４セル目)
データ一覧
1.物件データのカラム名(boston.feature_names)
・CRIM・・・犯罪発生率（人口単位）
・ZN・・・25,000平方フィート以上の住宅区画の割合
・INDUS・・・非小売業の土地面積の割合（人口単位）
・CHAS・・・チャールズ川沿いかどうか（1:Yes、0:No）
・NOX・・・窒素酸化物の濃度（pphm単位）
・RM・・・1戸あたりの平均部屋数
・AGE・・・1940年よりも前に建てられた家屋の割合
・DIS・・・ボストンの主な5つの雇用圏までの重み付きの郷里
・RAD・・・幹線道路へのアクセス指数
・TAX・・・10,000ドルあたりの所得税率
・PTRATIO・・・教師あたりの生徒の数（人口単位）
・B・・・アフリカ系アメリカ人居住者の割合（人口単位）
・LSTAT・・・低所得者の割合
2.物件の値段(boston.target)

最後に、ADMMを使用したアルゴリズムでの予測モデルの精度を確かめるためにscikit-learnのlinear_model(Coordinate Descent)と比較しています。(９〜１０セル目)

# Dependency
使用言語：Python3.7.1
環境：jupyter Notebook (version 5.7.4)

# Authors
Kazuki Ogiwara
