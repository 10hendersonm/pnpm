# @pnpm/plugin-commands-config

## 1.0.15

### Patch Changes

- @pnpm/config@16.6.1
- @pnpm/cli-utils@1.0.33

## 1.0.14

### Patch Changes

- Updated dependencies [59ee53678]
  - @pnpm/config@16.6.0
  - @pnpm/cli-utils@1.0.32

## 1.0.13

### Patch Changes

- @pnpm/config@16.5.5
- @pnpm/cli-utils@1.0.31

## 1.0.12

### Patch Changes

- @pnpm/config@16.5.4
- @pnpm/cli-utils@1.0.30

## 1.0.11

### Patch Changes

- @pnpm/config@16.5.3
- @pnpm/cli-utils@1.0.29

## 1.0.10

### Patch Changes

- @pnpm/config@16.5.2
- @pnpm/cli-utils@1.0.28

## 1.0.9

### Patch Changes

- @pnpm/config@16.5.1
- @pnpm/cli-utils@1.0.27

## 1.0.8

### Patch Changes

- Updated dependencies [28b47a156]
  - @pnpm/config@16.5.0
  - @pnpm/cli-utils@1.0.26

## 1.0.7

### Patch Changes

- @pnpm/config@16.4.3
- @pnpm/cli-utils@1.0.25

## 1.0.6

### Patch Changes

- @pnpm/config@16.4.2
- @pnpm/cli-utils@1.0.24

## 1.0.5

### Patch Changes

- @pnpm/config@16.4.1
- @pnpm/cli-utils@1.0.23

## 1.0.4

### Patch Changes

- f76a39973: `pnpm config set key=value` should work the same as `pnpm config set key value` [#5889](https://github.com/pnpm/pnpm/issues/5889).
- Updated dependencies [3ebce5db7]
  - @pnpm/config@16.4.0
  - @pnpm/error@4.0.1
  - @pnpm/cli-utils@1.0.22

## 1.0.3

### Patch Changes

- Updated dependencies [1fad508b0]
  - @pnpm/config@16.3.0
  - @pnpm/cli-utils@1.0.21

## 1.0.2

### Patch Changes

- @pnpm/cli-utils@1.0.20
- @pnpm/config@16.2.2

## 1.0.1

### Patch Changes

- 83a627a25: The config command should work with the `--location=global` CLI option [#5841](https://github.com/pnpm/pnpm/issues/5841).
- Updated dependencies [d71dbf230]
  - @pnpm/config@16.2.1
  - @pnpm/cli-utils@1.0.19

## 1.0.0

### Major Changes

- 841f52e70: pnpm gets its own implementation of the following commands:

  - `pnpm config get`
  - `pnpm config set`
  - `pnpm config delete`
  - `pnpm config list`

  In previous versions these commands were passing through to npm CLI.

  PR: [#5829](https://github.com/pnpm/pnpm/pull/5829)
  Related issue: [#5621](https://github.com/pnpm/pnpm/issues/5621)

### Patch Changes

- Updated dependencies [841f52e70]
  - @pnpm/config@16.2.0
  - @pnpm/cli-utils@1.0.18
