# @pnpm/render-peer-issues

## 1.1.2

### Patch Changes

- Updated dependencies [b138d048c]
  - @pnpm/types@7.10.0

## 1.1.1

### Patch Changes

- Updated dependencies [26cd01b88]
  - @pnpm/types@7.9.0

## 1.1.0

### Minor Changes

- b5734a4a7: When reporting unmet peer dependency issues, if the peer dependency is resolved not from a dependency installed by the user, then print the name of the parent package that has the bad peer dependency installed as a dependency.

  ![](https://i.imgur.com/0kjij22.png)

### Patch Changes

- Updated dependencies [b5734a4a7]
  - @pnpm/types@7.8.0

## 1.0.2

### Patch Changes

- 6058f76cd: When printing peer dependency issues, print the "\*" range in double quotes. This will make it easier to copy the package resolutions and put them to the end of a `pnpm add` command for execution.

## 1.0.1

### Patch Changes

- a087f339e: A new line should be between the summary about conflicting peers and non-conflicting ones.
- Updated dependencies [6493e0c93]
  - @pnpm/types@7.7.1

## 1.0.0

### Major Changes

- ba9b2eba1: Initial release.

### Patch Changes

- Updated dependencies [ba9b2eba1]
  - @pnpm/types@7.7.0