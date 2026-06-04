# Velt Framework

Official Velt framework meta-package and integration layer.

## Role

This repository assembles the official Velt components without replacing them. It exists to document and enforce compatible versions between:

- `veltphp/kernel`
- `veltphp/http`
- `veltphp/ui`
- `veltphp/database`
- `veltphp/orm`
- `veltphp/cli`
- `veltphp/preview`
- `veltphp/skeleton`

## Skeleton vs Framework

`veltphp/skeleton` is the application template copied or installed by developers.

`veltphp/framework` is the Composer-level assembly package that defines which Velt components work together.

## Module 3 Goal

The first Module 3 task is to create the framework meta-package, document local development with Composer path repositories, and maintain a compatibility matrix for multi-repo work.
