# Description

Template for library submodules of a microservice.

## Folder structure

```
├── src
│   ├── entities // TypeORM entities
│   ├── options // NestJS gRPC options
│   ├── protos // gRPC protobuf files
│   └── utils // Utility functions
├── .gitignore
├── package.json
├── README.md
├── tsconfig.json
├── yarn.lock
```

# Bootstrap

## Dependency Installation

```
npm i -g yarn
yarn install
```

## Build

```
yarn build
```

```
yarn build:proto
```
