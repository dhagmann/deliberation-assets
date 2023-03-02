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
  "launchDate": "18 Nov 2022 13:15:00 EST",
  "lastEntryDate": "18 Nov 2022 13:45:00 EST",
  "closeDate": "18 Nov 2022 14:45:00 EST"
}
```
