# litestream-demo

1. create a sqlite file
```bash
$ mkdir -p data 
$ sqlite3
sqlite> .open ./data/data.db
sqlite> .exit
```

2. create a s3 bucket following the [guide](https://litestream.io/guides/s3/) 

3. create a `litestream.yml` file and a sqlite database
```bash
./dev init
```

4. wirte down your aws credentials in `litestream.yml`

5. run litestream directly to validate your setup
```bash
./dev lite
```
