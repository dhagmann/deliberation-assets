# So Good exercise

Questions to include:

- self monitoring

- add some padding on the no-discussion display
- line wrap long display responses so they don't spill out the box.

```json
{
  "batchName": "demo",
  "preregister": "false",
  "treatmentFile": "projects/constructive_disagreement/so_good/so_good.treatments.yaml",
  "dispatchWait": 1,
  "introSequence": "baseline",
  "treatments": ["baseline"],
  "cdn": "local",
  "exitCodeStem": "SGDemo",
  "videoStorageLocation": "deliberation-lab-recordings-test",
  "dataRepos": [
    {
      "owner": "Watts-Lab",
      "repo": "deliberation-data-test",
      "branch": "main",
      "directory": "demo"
    }
  ]
}
```

demo on the prod server

```json
{
  "batchName": "demo",
  "preregister": "false",
  "treatmentFile": "projects/constructive_disagreement/so_good/so_good.treatments.yaml",
  "dispatchWait": 1,
  "introSequence": "baseline",
  "treatments": ["baseline"],
  "cdn": "prod",
  "videoStorageLocation": "deliberation-lab-recordings-test",
  "dataRepos": [
    {
      "owner": "JamesPHoughton",
      "repo": "so-good-study",
      "branch": "main",
      "directory": "data"
    }
  ]
}
```

MTurk test

```json
{
  "batchName": "turkPilot",
  "preregister": "false",
  "treatmentFile": "projects/constructive_disagreement/so_good/so_good.treatments.yaml",
  "dispatchWait": 20,
  "introSequence": "baseline",
  "launchDate": "17 Jan 2024 13:00:00 EST",
  "treatments": ["baseline"],
  "cdn": "prod",
  "exitCodeStem": "tP117",
  "videoStorageLocation": "deliberation-lab-recordings-icbs",
  "awsRegion": "eu-west-2",
  "dataRepos": [
    {
      "owner": "JamesPHoughton",
      "repo": "so-good-study",
      "branch": "main",
      "directory": "data"
    }
  ],
  "preregRepos": [
    {
      "owner": "JamesPHoughton",
      "repo": "so-good-study",
      "branch": "main",
      "directory": "preregistration"
    }
  ]
}
```
