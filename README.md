# Agent Memory

This repository collects agent-memory research code for collaboration and
reproducible experiments.

## LoCoMo-Conv

`LoCoMo-Conv/` is a clean snapshot of the official
[`MiuLab/LoCoMo-Conv`](https://github.com/MiuLab/LoCoMo-Conv) repository.

- Imported source commit: `1925e92`
- Imported at: 2026-10-26
- Scope: Git-tracked files from the official repository `HEAD`
- Local reproduction edits and generated experiment outputs are not included

The source is kept in a subdirectory so that additional memory-system code and
reproduction experiments can be added independently later.

## Update the upstream snapshot

From `LoCoMo-Conv/`, add the upstream repository if it is not already configured:

```bash
git remote add upstream https://github.com/MiuLab/LoCoMo-Conv.git
```

Because this import is preserved as a directory snapshot rather than a Git
submodule, upstream updates should be reviewed and copied deliberately. Commit
each update separately so that the repository remains easy to roll back.

## Provenance

Please cite and follow the upstream project's distribution and licensing terms
when using the LoCoMo-Conv code or data.
