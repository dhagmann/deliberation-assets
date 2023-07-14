[![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

This repository contains assets served to participants in deliberation experiments.

This repo is synced to a CDN, but also provides version control for files, so that
we can refer to the precise version of a file when tracing the data.

During dev, you can start this as a local webserver by running:

```
npx http-server --cors -a localhost -p 9090
```

npx serve -l 9091

```json
{
  "batchName": "dev",
  "treatmentFile": "projects/example/treatments.test.yaml",
  "dispatchWait": 1,
  "introSequence": "cypress_intro",
  "cdn": "test",
  "treatments": ["cypress_omnibus"]
}
```
