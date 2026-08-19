<p align="center">
  <h1 align="center">Which Tokens Drive Emergent Misalignment</h1>
  <p align="center"><strong>Attribute emergent misalignment to token-level patterns in fine-tuning documents on small models.</strong></p>
</p>

---

## Overview

This repository implements experimental profiles for **Which Tokens Drive Emergent Misalignment**. Config, caching, hooks, metrics, ablations, reporting, and CI support local pilots on small open-weight models.

Hypothesis (one line): Attribute emergent misalignment to token-level patterns in fine-tuning documents on small models.

## Status

Shared infrastructure is in place; domain stages must pass harness validation before any measured claim.

| Command | Purpose |
|---|---|
| `make install-dev` | editable install + pinned requirements |
| `make test` | full unit suite |
| `make ci` | lint + test + typecheck |
| `make pilot` | end-to-end pilot profile |
