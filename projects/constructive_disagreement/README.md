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

```json
{
  "batchName": "demo",
  "treatmentFile": "projects/constructive_disagreement/hidden_profile/treatments_baker_2010.yaml",
  "launchDate": "",
  "dispatchWait": 1,
  "exitCodeStem" : "none",
  "cdn": "local",
  "introSequence": "baseline",
  "consentAddendum": "projects/constructive_disagreement/00_consentAddendum.md",
  "treatments": ["baseline"],
  "videoStorageLocation": "deliberation-lab-recordings-test",
  "preregister": false,
  "dataRepos": [
    {
      "owner": "JamesPHoughton",
      "repo": "constructive-disagreement",
      "branch": "main",
      "directory": "test"
    }
  ]
}
```

# Demo config for super sabbatical
```json
{
  "batchName": "super_sabbatical",
  "treatmentFile": "projects/constructive_disagreement/hidden_profile/treatments_baker_2010.yaml",
  "launchDate": "",
  "dispatchWait": 120,
  "exitCodeStem" : "none",
  "cdn": "local",
  "introSequence": "baseline",
  "consentAddendum": "projects/constructive_disagreement/00_consentAddendum.md",
  "treatments": ["baseline"],
  "videoStorageLocation": "deliberation-lab-recordings-test",
  "preregister": false,
  "dataRepos": [
    {
      "owner": "JamesPHoughton",
      "repo": "constructive-disagreement",
      "branch": "main",
      "directory": "test"
    }
  ]
}
```

```json
{
  "batchName": "super_sabbatical",
  "introSequence": "baseline",
  "treatmentFile": "projects/constructive_disagreement/super_sabbatical/super_sabbatical.treatments.yaml",
  "dispatchWait": 120,
  "exitCodeStem" : "none",
  "treatments": [
        "negotiation",
        "unmatched_sorry"
    ],
    "payoffs": [
        1,
        0.1    
    ],
  "cdn": "local",
  "videoStorageLocation": "deliberation-lab-recordings-test",
  "preregister": false,
  "dataRepos": [
    {
      "owner": "JamesPHoughton",
      "repo": "constructive-disagreement",
      "branch": "main",
      "directory": "test"
    }
  ]
}
```