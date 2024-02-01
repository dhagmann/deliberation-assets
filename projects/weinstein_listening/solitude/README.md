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
