# pre-commit-golang

Golang hooks for [pre-commit-hooks](https://pre-commit.com)

## Using these hooks

Add this to your `.pre-commit-config.yaml`

```sh
- repo: https://github.com/aeswibon/pre-commit-golang
  rev: master
  hooks:
    - id: go-vet
```

## Available hooks

- `go-vet`: Runs `go vet` to find any suspicious constructs
