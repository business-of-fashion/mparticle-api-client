# Documenation
 
This package is created using [OpenAPI Generator](https://openapi-generator.tech), according to the configuration defined in `mparticle.oas.yaml`.


To install the OpenAPI Generator CLI
```bash
npm install @openapitools/openapi-generator-cli -D
```

To generate the PHP client
```bash
node_modules/@openapitools/openapi-generator-cli/bin/openapi-generator generate -i mparticle.oas.yaml -g php
```