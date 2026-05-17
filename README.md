# Project India Data

Private data repository for Project India gathered research evidence.

This repo is written by the scheduled collector workflow in `Project-India`.

Expected layout:

```text
data/<topic-slug>/raw/<sha>.<raw-extension>
data/<topic-slug>/raw/<sha>.txt
data/<topic-slug>/raw/<sha>.json
data/<topic-slug>/raw/<sha>.analysis.json
```

The main code repo should stay focused on collectors/workflows. This repo stores gathered evidence for downstream analysis.
