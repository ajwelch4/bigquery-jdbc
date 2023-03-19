# BigQuery JDBC
Publish BigQuery JDBC drivers to a private Maven repo on S3

Google issue tracker: https://issuetracker.google.com/issues/180413368

[JDBC Download](https://cloud.google.com/bigquery/docs/reference/odbc-jdbc-drivers#current_jdbc_driver)

```shell
wget https://storage.googleapis.com/simba-bq-release/jdbc/SimbaBigQueryJDBC42-1.3.2.1003.zip
unzip SimbaBigQueryJDBC42-1.3.2.1003.zip -d bigquery-jdbc 
rm -rf SimbaBigQueryJDBC42-1.3.2.1003.zip
./gradlew build
```
