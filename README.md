# Deliberation Assets
This repository contains assets served to participants in deliberation experiments.

## License
The collection presented here is the work of a variety of authors. Unless otherwise specified in 'README.md`or`LICENSE` files within subfolders, the original authors retain all rights to the materials presented.


## Production Usage

This repo is synced to a CDN, but also provides version control for files, so that
we can refer to the precise version of a file when tracing the data.

## Dev Usage

During dev, you can start this as a local webserver by running:

```bash
npx http-server --cors -a localhost -p 9091
```
or:

```bash
npx http-server --cors -a 127.0.0.1 -p 9091
```

or:

```bash
npx serve -l 9091
```

In the deliberation-empirica admin, specify the cdn as:
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
