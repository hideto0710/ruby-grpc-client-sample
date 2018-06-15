ruby-client
===

```
bundle exec grpc_tools_ruby_protoc \
  --proto_path=./protos/scala-grpc-sample/src/main/protobuf \
  --ruby_out=lib \
  --grpc_out=lib \
  ./protos/scala-grpc-sample/src/main/protobuf/hello.proto
```
```
bundle exec ./client.rb test
```
