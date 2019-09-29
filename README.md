# spanner
Google Cloud Spannerで試したサンプルやノウハウとかを入れておくリポジトリ

## gcloud

```
gcloud spanner databases execute-sql {DATABASE_ID} --instance={INSTANCE_ID} --sql='SELECT * FROM Singers LIMIT 100'
```
