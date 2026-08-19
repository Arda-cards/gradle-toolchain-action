# Gradle Toolchain Setup Action

[![ci](https://github.com/Arda-cards/gradle-toolchain-action/actions/workflows/ci.yaml/badge.svg)](https://github.com/Arda-cards/gradle-toolchain-action/actions/workflows/ci.yaml)
[CHANGELOG.md](CHANGELOG.md)

This action set up the toolchain required for a Gradle project. It extracts its information from the gradle configuration itself.

## Arguments

See [action.yaml](action.yaml).

## Usage

```yaml
steps:
  - name: "Setup gradle toolchain"
    uses: Arda-cards/gradle-toolchain-action@dna/PDEV-1414
    with:
      token: ${{ inputs.token }}
```

## Permission Required

```yaml
  permissions:
    {}
```
