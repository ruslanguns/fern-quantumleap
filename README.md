# QuantumLeap Fern SDK

### Prerequisites

1. NodeJS, NPM
2. Install fern-api

```bash
npm install -g fern-api
```

### Usage

1. Convert OpenAPI Reference from v2 to v3

https://editor.swagger.io/

2. Run fern init

```bash
fern init --openapi openapi_v3.yaml
```

3. Run fern generate

```bash
fern generate
```

### References

- QuantumLeap API Reference:
  - [Repository](https://github.com/FIWARE-GEs/quantum-leap/blob/master/specification/quantumleap.yml)
  - [Swagger](https://app.swaggerhub.com/apis/smartsdk/ngsi-tsdb)
- [Fern](https://docs.buildwithfern.com/)
- [Fern Typescript-SDK](https://docs.buildwithfern.com/showcase/typescript-sdk)
