## TypeScript

These settings apply only when `--typescript` is specified on the command line.
Please also specify `--typescript-sdks-folder=<path to root folder of your azure-sdk-for-js clone>`.

``` yaml $(typescript)
typescript:
  azure-arm: true
  package-name: "@azure/arm-iotspaces"
  output-folder: "$(typescript-sdks-folder)/sdk/iotspaces/arm-iotspaces"
  generate-metadata: true
```
