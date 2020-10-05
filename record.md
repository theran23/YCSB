월요일


1. rocksdb clone
```
git clone https://github.com/facebook/rocksdb
```

2. compile
```
cd rocksdb
make static_lib
```

3.configuration

INI FILE 수정 : 소이언니의 RocskDBClient.java 보고 rocksdb_option_file.ini 수정 ()

~/YCSB/rocksdb/src/main/java/site/ycsb/db/rocksdb/RocksDBClient.java 에서

String PROPERTY_ROCKSDB_DIR: rocksdb data dir path

String PROPERTY_ROCKSDB_OPTIONS_FILE : ini file path 로 
