# LSTM

### 執行前準備
1. 將 label 的檔案（HM10_label_p.xlsx）放入雲端，並在 load label_xlsx 中的 xlsx_name 填上相對路徑。
2. 將 dataset 的檔案（HM_dataset）放入雲端，並在 load sample_json 中的 dataset_path 填上相對路徑。

### 執行方式
點選「執行階段」中的「全部執行」，即可執行所有程式。

### 備註
為了避免每次執行都要重複讀取 json，我們將裁切好的資料分別存成 X_train_dist.txt、X_test_dist.txt、y_train_dist.txt、y_test_dist.txt。每次訓練時只要讀取這四個檔案即可訓練。