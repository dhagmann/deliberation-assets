This case is (heavily) adapted from Baker 2010. In this adaptation, each participant is given a particular role in the organization and position to advocate for. In addition the information about each candidate is modified to give each role a preferred candidate.

This makes the exercise something of a hybrid between a pure hidden-profile task in which the learning objective is to overcome shared information bias, and a negotiation in which parties have competing goals.

## Dev

```json
{
  "batchName": "demo",
  "treatmentFile": "projects/constructive_disagreement/hidden_profile/treatments_hp.yaml",
  "launchDate": "",
  "dispatchWait": 1,
  "introSequence": "psychometrics",
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
