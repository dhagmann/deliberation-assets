# Team

- Burint Bevis
- Mark Kennedy
- James Houghton
- Emily Hu

# Demo config

```json
{
  "batchName": "demo",
  "treatmentFile": "projects/example/treatments.test.yaml",
  "launchDate": "",
  "dispatchWait": 1,
  "introSequence": "baseline",
  "consentAddendum": "projects/constructive_disagreement/00_consentAddendum.md",
  "cdn": "local",
  "treatments": ["baseline"],
  "videoStorageLocation": "deliberation-lab-recordings-test",
  "preregister": true,
  "dataRepos": [
    {
      "owner": "Watts-Lab",
      "repo": "deliberation-data-test",
      "branch": "main",
      "directory": "cypress_test_exports"
    },
    {
      "owner": "Watts-Lab",
      "repo": "deliberation-data-test",
      "branch": "main",
      "directory": "cypress_test_exports2"
    }
  ],
  "preregRepos": [
    {
      "owner": "Watts-Lab",
      "repo": "deliberation-data-test",
      "branch": "main",
      "directory": "preregistration"
    }
  ]
}
```
