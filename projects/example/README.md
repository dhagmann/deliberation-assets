# Example Study

This project holds example files used to demonstrate how to construct the various resources needed by the platform, and that are also used in the test suite.

To run a single-player demo, use a variation on the config:

```json
{
  "batchName": "labDemo",
  "treatmentFile": "projects/example/treatments.test.yaml",
  "dispatchWait": 1,
  "useTreatments": ["demo1p"],
  "useIntroSequence": "cypress_standard",
  "platformConsent": "US",
  "consentAddendum": "projects/example/consentAddendum.md",
  "launchDate": "01 Mar 2023 23:30:00 EST"
}
```

```json
{
  "batchName": "labDemo",
  "treatmentFile": "projects/example/treatments.test.yaml",
  "dispatchWait": 1,
  "useTreatments": ["demo1p"]
}
```

## Demo

```json
{
  "batchName": "labDemo",
  "useData": "false",
  "treatmentFile": "projects/example/treatments.demo.yaml",
  "dispatchWait": 1,
  "introSequence": "demoIntro",
  "treatments": ["demo_2p"],
  "cdn": "test",
  "platformConsent": "US",
  "consentAddendum": "projects/example/consentAddendum.md",
  "launchDate": "14 Jul 2023 18:45:00 CEST"
}
```

```json
{
  "batchName": "labDemo",
  "useData": "false",
  "treatmentFile": "projects/example/treatments.demo.yaml",
  "dispatchWait": 1,
  "introSequence": "demoIntro",
  "treatments": ["demo_2p"],
  "cdn": "test",
  "platformConsent": "US",
  "consentAddendum": "projects/example/consentAddendum.md",
  "videoStorageLocation": "deliberation-lab-recordings-test"
}
```
