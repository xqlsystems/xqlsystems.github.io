---
title: xql.systems
description-meta: Towards Relational Arrays
---

![](assets/logo.png)

_We're on a mission to prove that relational algebra is as important to science and machine learning as linear algebra or calculus._

We're building a **SQL layer on top of [Zarr](https://zarr.dev/)** — bringing
familiar, declarative SQL querying to multidimensional array data.

This organization hosts all the repositories related to that effort.

## What we're working on

Zarr is a great format for chunked, compressed N-dimensional arrays, but
querying it usually means writing imperative array code. Our goal is to let you
point SQL at Zarr stores and get back the data you want, with the array world
and the relational world meeting in the middle.

## Key Projects

- **[Xarray-SQL](https://xql.systems/xarray-sql/)** — Briding [Xarray](https://xarray.dev) - labeled, multidimensional array model and
  the bridge to Zarr - with SQL.
- **[DuckDB-Zarr](https://github.com/xqlsystems/duckdb-zarr)** — Zarr integration with [DuckDB's](http://duckdb.org/) in-process analytical SQL engine.
- **[ddx](https://github.com/xqlsystems/ddx)** - JAX style automatic differentiation in SQL. We want to make differentiable programming declarative and relational.

## Join us

Raise an issue, file a PR, or [chat with us on Discord](https://discord.gg/6JwnQDwGph).