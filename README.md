# MCP tools and a reliable agent

[![CI](https://github.com/AbirHasanPiash/orders-mcp-agent/actions/workflows/ci.yml/badge.svg)](https://github.com/AbirHasanPiash/orders-mcp-agent/actions/workflows/ci.yml)

> **Status: planned. Work starts Feb 2027.**
> This README is the plan. Each number appears only after it has been measured.

A TypeScript MCP server for orders and refunds, and an agent measured by pass^k, cost per task and how safely it fails.

Demo (2 min): _coming_ · Live: _coming_ · Write-up: _coming_

## Problem

Who has it, what "good" looks like for them, and why it is hard. Three lines.

## Results

| Version  | Metric A | Metric B | p95 latency | Cost / 1k requests |
|----------|----------|----------|-------------|--------------------|
| Baseline | –        | –        | –           | –                  |

Eval set: _N_ items, _source_, labelled by _how_. Judge agreement with human labels: _x_% (n=_n_).
Intervals: 95% bootstrap.

## Architecture

_Diagram goes here._

- Ingestion / input: ...
- Core logic: ...
- Evals: ...
- Observability: ...

## What I tried that didn't work

- _Experiment_: _what happened, and why I think it happened._

## Security and privacy

Threats considered, mitigations, what is out of scope.

## Run it

```bash
git clone https://github.com/AbirHasanPiash/orders-mcp-agent.git
cd orders-mcp-agent
cp .env.example .env   # then add your own keys
make setup             # install dependencies and git hooks
make check             # lint, format check, tests
make eval              # eval suite (calls models, uses API quota)
```

## Tests and CI

Unit tests, an eval subset with pass thresholds, and lint checks on every push and pull request.

## With two more weeks I would

- ...

---

License: MIT. Part of a year-long build plan by [AbirHasanPiash](https://github.com/AbirHasanPiash).
