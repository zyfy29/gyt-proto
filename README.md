# Proto files for GYT project

## generate python code

```bash
python -m grpc_tools.protoc -I./proto --python_out=. --grpc_python_out=. ./proto/legacy_service.proto
```
