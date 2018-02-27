# Product Service API
Proposal of a Future Product Service API.

![diagram](state-diagram.jpg)

## Compile Data Model
To compile the JSON Schema data model into OAS2 install the supermodel cli tool

```
$ npm i -g supermodel-cli
```

Then run:

```
$ cd supermodel
$ supermodel compile-schema adidas/ > compiled.yaml && supermodel oas2 compiled.yaml > oas2.yaml
```

The result file is the `definitions` sections of the OAS2. 
