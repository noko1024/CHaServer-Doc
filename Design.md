1. mapについて  
プログラム上では2次元配列を用いて保存します。  
外部との共有ではCSVに変換後、Blobで共有を予定しています。  

2. DBの形式定義
     1. postgreSQL
          - roomID : ULID
          - log :　下に記載
          - mapHash : SHA-256
          - mapData : 変換したCSVのBlob 
     2.  Redis
          - roomID : ULID
          - cashData : 下に記載

3. CHaserLogの形式について
     どうしよう！
4. CashDataの形式について  
