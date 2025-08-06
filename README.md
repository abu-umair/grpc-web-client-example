# JavaScript gRPC Web Client

- copas proto dari project sebelumnya
- buat folder pb

- generate proto
```bash
npx protoc --ts_out ./pb --proto_path ./proto user/user.proto

```

install runtime
```bash
npm install @protobuf-ts/runtime

```

install runtime-rpc
```bash
npm install @protobuf-ts/runtime-rpc

```

generate ulang base response (import gagal pada common, karena belum diinstall)
```bash
npx protoc --ts_out ./pb --proto_path ./proto common/base_response.proto

```

install grpcweb-transport
```bash
npm install @protobuf-ts/grpcweb-transport

```