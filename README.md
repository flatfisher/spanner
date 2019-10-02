# spanner
[Google Cloud Spanner](https://cloud.google.com/spanner/docs)で試したサンプルやノウハウとかを入れておくリポジトリ

## gcloud

```
// SQLの実行
gcloud spanner databases execute-sql {DATABASE_ID} --instance={INSTANCE_ID} --sql='SELECT * FROM Singers LIMIT 100'
```
