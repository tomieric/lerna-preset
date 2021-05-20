# lerna-preset

> This is a preset template for lerna project

## Usage

```bash
git clone https://github.com/tomieric/lerna-preset.git --depth=1 [project]
```

## Create Project

```bash
npx lerna create @tomieric/utils
```

## Add Module

```bash
npx lerna add vue-router --peer --scope=@tomieric/utils

npx lerna add esbuild --dev --scope=@tomieric/utils
```