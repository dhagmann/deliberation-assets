Todo:

- update qualtrics server name in env variables on our server

```json
{
  "batchName": "demo",
  "treatmentFile": "projects/weinstein_listening/solitude/solitude.treatments.yaml",
  "dispatchWait": 1,
  "preregister": false,
  "treatments": ["baseline_english"],
  "videoStorageLocation": "none",
  "introSequence": "baseline_english",
  "exitCodeStem": "none",
  "cdn": "local",
  "dataRepos": [
    {
      "owner": "Watts-Lab",
      "repo": "deliberation-data-test",
      "branch": "main",
      "directory": "demo"
    }
  ],
  "preregRepos": [
    {
      "owner": "JamesPHoughton",
      "repo": "listening-study",
      "branch": "main",
      "directory": "data"
    }
  ]
}
```

## Prod config

```json
{
  "batchName": "study_RA1",
  "treatmentFile": "projects/weinstein_listening/solitude/solitude.treatments.yaml",
  "dispatchWait": 1,
  "preregister": false,
  "treatments": ["baseline_english"],
  "videoStorageLocation": "none",
  "introSequence": "baseline_english",
  "exitCodeStem": "none",
  "cdn": "prod",
  "dataRepos": [
    {
      "owner": "JamesPHoughton",
      "repo": "listening-study",
      "branch": "main",
      "directory": "solitude_data"
    }
  ],
  "preregRepos": [
    {
      "owner": "JamesPHoughton",
      "repo": "listening-study",
      "branch": "main",
      "directory": "solitude_data"
    }
  ]
}
```

Hebrew

```json
{
  "batchName": "demo",
  "treatmentFile": "projects/weinstein_listening/solitude/solitude.treatments.yaml",
  "dispatchWait": 1,
  "preregister": false,
  "treatments": ["baseline_hebrew"],
  "videoStorageLocation": "none",
  "introSequence": "baseline_hebrew",
  "exitCodeStem": "none",
  "cdn": "local",
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
