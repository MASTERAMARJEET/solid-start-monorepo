# Solid Start bug reproduction

This repo demonstrates the fact the solid-start dev server is failing in a monorepo setup

yarn: v1.22.18
solid-start: v0.1.5
pnpm: v7.13.2

## Test yarn

```bash
rm -rf **/node_modules yarn.lock && yarn && yarn dev
```

## Test pnpm

```bash
rm -rf **/node_modules pnpm-lock.yaml && pnpm i && pnpm dev
```
