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
  "introSequence": "baseline",
  "consentAddendum": "projects/constructive_disagreement/00_consentAddendum.md",
  "treatmentFile": "projects/constructive_disagreement/super_sabbatical/super_sabbatical.treatments.yaml",
  "dispatchWait": 10,
  "exitCodeStem" : "none",
  "treatments": ["negotiation"],
    "payoffs": [1],
  "cdn": "local",
  "videoStorageLocation": "deliberation-lab-recordings-test",
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

# Demo config for super sabbatical (WBL)
```json
{
  "batchName": "demo",
  "cdn": "prod",
  "treatmentFile": "projects/constructive_disagreement/super_sabbatical_wbl/super_sabbatical_wbl.treatments.yaml",
  "customIdInstructions": "shared/id_instructions/WBL.md",
  "platformConsent": "US",
  "consentAddendum": "projects/constructive_disagreement/00_consentAddendum.md",
  "checkAudio": true,
  "checkVideo": true,
  "introSequence": "baseline",
  "treatments": ["negotiation"],
  "payoffs": "equal",
  "knockdowns": "none",
  "dispatchWait": 10,
  "launchDate": "immediate",
  "centralPrereg": false,
  "preregRepos": [
    {
      "owner": "JamesPHoughton",
      "repo": "constructive-disagreement",
      "branch": "main",
      "directory": "test"
    }
  ],
  "dataRepos": [
    {
      "owner": "JamesPHoughton",
      "repo": "constructive-disagreement",
      "branch": "main",
      "directory": "test"
    }
  ],
  "videoStorage": {
    "bucket": "deliberation-lab-recordings-constructive-disagreement-us-east-1",
    "region": "us-east-1"
  },
  "exitCodes": "none"
}
```