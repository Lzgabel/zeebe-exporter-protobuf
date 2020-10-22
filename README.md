# zeebe-exporter-protobuf

This repository contains a [protobuf schema definition](https://github.com/zeebe-io/zeebe-exporter-protobuf/blob/master/src/main/proto/schema.proto) for exported records from Zeebe. It can be used by a Zeebe exporter to exchange/transmit exported records.

> 编译 schema.proto 文件
> 
> protoc ./src/main/proto/schema.proto  --java_out=src/main/java
