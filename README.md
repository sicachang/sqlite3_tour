# sqlite3_tour

# 進入sqlite3環境 (以 `digital.db` 為例)
```cmd
sqlite3.exe digital.db
```

# 執行sql腳本 
- 以 建立`資服業`資料表 `createTable_Information_service.sql` 為例)
```cmd
sqlite3.exe digital.db ".read createTable_Information_service.sql"
```
- 以 建立`餐飲業`資料表 `createTable_Catering.sql` 為例)
```cmd
sqlite3.exe digital.db ".read createTable_Caterin.sql"
```
- 以 建立`製造業` 資料表 createTable_manufacture.sql.sql` 為例)
```cmd
sqlite3.exe digital.db ".read createTable_manufacture.sql.sql"
```

# dbToCSV (以 `digital.db` `資服業` 資料表匯出CSV 為例)

# 進入sqlite3環境 
```cmd
.headers on
.mode csv
.output information_service.csv
select * from _資服業;
.quit
```

# (線上工具)
- csvToSQL
https://blog.pulipuli.info/2017/11/csv-to-sql-tablecsv-import-csv-file.html#postcatacsv-to-sql-tablecsv-import-csv-file.html0_anchor1 

# sqllite 操控介面
...未更新
