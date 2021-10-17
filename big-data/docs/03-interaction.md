```sql
CREATE EXTERNAL TABLE candles (dt date, volume FLOAT, open FLOAT, close FLOAT, high FLOAT, low FLOAT, adj FLOAT)
ROW FORMAT DELIMITED FIELDS TERMINATED BY ','
STORED AS TEXTFILE LOCATION '/user/admin/stocks';
```
