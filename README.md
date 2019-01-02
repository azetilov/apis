# APIs
Desin repository of the adidas API landscape.

## Supermodel Data Model
The data model is defined using <supermodel.io> models–that is a JSON Schema in YAML representation. These models are defined in the `supermodel/adidas` directory.

To compile the data model for use in OpenAPI Spec 2.0, install the [Supermodel CLI tool](https://github.com/supermodel/supermodel-cli):

```
$ npm install -g @supermodel/cli
```

and then run:

```
$ supermodel schema oas2 supermodel/adidas/product -o product.yaml
```
