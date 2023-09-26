# Team

- Burint Bevis
- Mark Kennedy
- James Houghton
- Emily Hu

# Demo config for lost at sea

```json
{
  "batchName": "demo",
  "treatmentFile": "projects/constructive_disagreement/treatments.yaml",
  "launchDate": "",
  "dispatchWait": 1,
  "introSequence": "baseline",
  "consentAddendum": "projects/constructive_disagreement/00_consentAddendum.md",
  "cdn": "local",
  "treatments": ["baseline"],
  "videoStorageLocation": "deliberation-lab-recordings-test",
  "preregister": false,
  "dataRepos": [
    {
      "owner": "Watts-Lab",
      "repo": "deliberation-data-test",
      "branch": "main",
      "directory": "cypress_test_exports"
    }
  ]
}
```

# Demo config for hidden profile baker

```json
{
  "batchName": "demo",
  "treatmentFile": "projects/constructive_disagreement/hidden_profile/treatments_baker_2010.yaml",
  "launchDate": "",
  "dispatchWait": 1,
  "introSequence": "baseline",
  "consentAddendum": "projects/constructive_disagreement/00_consentAddendum.md",
  "cdn": "local",
  "treatments": ["baseline"],
  "videoStorageLocation": "deliberation-lab-recordings-test",
  "preregister": false,
  "dataRepos": [
    {
      "owner": "Watts-Lab",
      "repo": "deliberation-data-test",
      "branch": "main",
      "directory": "cypress_test_exports"
    }
  ]
}
```
