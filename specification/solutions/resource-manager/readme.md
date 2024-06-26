# ManagedApplication

> see https://aka.ms/autorest

This is the AutoRest configuration file for managedApplication.

## Getting Started

To build the SDKs for My API, simply install AutoRest via `npm` (`npm install -g autorest`) and then run:

> `autorest readme.md`

To see additional help and options, run:

> `autorest --help`

For other options on installation see [Installing AutoRest](https://aka.ms/autorest/install) on the AutoRest github page.

---

## Configuration

### Basic Information

These are the global settings for the managedApplication.

```yaml
openapi-type: arm
openapi-subtype: rpaas
tag: package-managedapplications-2021-07
```

``` yaml $(package-managedapplications)
tag: package-managedapplications-2021-07
```


### Tag: package-managedapplications-2021-07

These settings apply only when `--tag=package-managedapplications-2021-07` is specified on the command line.

``` yaml $(tag) == 'package-managedapplications-2021-07'
input-file:
- Microsoft.Solutions/stable/2021-07-01/managedapplications.json
```

### Tag: package-managedapplications-2021-02

These settings apply only when `--tag=package-managedapplications-2021-02` is specified on the command line.

``` yaml $(tag) == 'package-managedapplications-2021-02'
input-file:
- Microsoft.Solutions/preview/2021-02-01-preview/managedapplications.json
```

### Tag: package-managedapplications-2020-08

These settings apply only when `--tag=package-managedapplications-2020-08` is specified on the command line.

``` yaml $(tag) == 'package-managedapplications-2020-08'
input-file:
- Microsoft.Solutions/preview/2020-08-21-preview/managedapplications.json
```

### Tag: package-managedapplications-2019-07

These settings apply only when `--tag=package-managedapplications-2019-07` is specified on the command line.

``` yaml $(tag) == 'package-managedapplications-2019-07'
input-file:
- Microsoft.Solutions/stable/2019-07-01/managedapplications.json
```

### Tag: package-managedapplications-2018-09

These settings apply only when `--tag=package-managedapplications-2018-09` is specified on the command line.

``` yaml $(tag) == 'package-managedapplications-2018-09'
input-file:
- Microsoft.Solutions/preview/2018-09-01-preview/managedapplications.json
```

### Tag: package-managedapplications-2018-06

These settings apply only when `--tag=package-managedapplications-2018-06` is specified on the command line.

``` yaml $(tag) == 'package-managedapplications-2018-06'
input-file:
- Microsoft.Solutions/stable/2018-06-01/managedapplications.json
```

### Tag: package-managedapplications-2018-03

These settings apply only when `--tag=package-managedapplications-2018-03` is specified on the command line.

``` yaml $(tag) == 'package-managedapplications-2018-03'
input-file:
- Microsoft.Solutions/stable/2018-03-01/managedapplications.json
```

### Tag: package-managedapplications-2018-02

These settings apply only when `--tag=package-managedapplications-2018-02` is specified on the command line.

``` yaml $(tag) == 'package-managedapplications-2018-02'
input-file:
- Microsoft.Solutions/stable/2018-02-01/managedapplications.json
```

### Tag: package-managedapplications-2017-12

These settings apply only when `--tag=package-managedapplications-2017-12` is specified on the command line.

``` yaml $(tag) == 'package-managedapplications-2017-12'
input-file:
- Microsoft.Solutions/stable/2017-12-01/managedapplications.json
```

### Tag: package-managedapplications-2017-09

These settings apply only when `--tag=package-managedapplications-2017-09` is specified on the command line.

``` yaml $(tag) == 'package-managedapplications-2017-09'
input-file:
- Microsoft.Solutions/stable/2017-09-01/managedapplications.json
```

---

# Code Generation

## Swagger to SDK

This section describes what SDK should be generated by the automatic system.
This is not used by Autorest itself.

```yaml $(swagger-to-sdk)
swagger-to-sdk:
  - repo: azure-sdk-for-python-track2
  - repo: azure-sdk-for-java
  - repo: azure-sdk-for-go
  - repo: azure-sdk-for-js
  - repo: azure-sdk-for-ruby
    after_scripts:
      - bundle install && rake arm:regen_all_profiles['azure_mgmt_managedApplication']
  - repo: azure-powershell
```

## Go

See configuration in [readme.go.md](./readme.go.md)

## Python

See configuration in [readme.python.md](./readme.python.md)

## Ruby

See configuration in [readme.ruby.md](./readme.ruby.md)

## TypeScript

See configuration in [readme.typescript.md](./readme.typescript.md)

## CSharp

See configuration in [readme.csharp.md](./readme.csharp.md)

## Java

See configuration in [readme.java.md](./readme.java.md)
