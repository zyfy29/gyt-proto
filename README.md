# Proto files for GYT project

## generate python code

```bash
python -m grpc_tools.protoc -I./proto --python_out=. --grpc_python_out=. ./proto/legacy_service.proto
```

## generate go code

```bash
protoc --proto_path=proto --go_out=latency --go_opt=paths=source_relative --go-grpc_out=latency --go-grpc_opt=paths=source_relative proto/legacy_service.proto
```
