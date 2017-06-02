# problem statement
runs npm install

# example usage

> note: in examples, VERSION represents a version of the npm.install pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/npm.install#VERSION
```

## run

```
opctl run github.com/opspec-pkgs/npm.install#VERSION
```

## compose

```yaml
op:
  pkg: { ref: github.com/opspec-pkgs/npm.install#VERSION }
  inputs: { srcDir, registry }
```
