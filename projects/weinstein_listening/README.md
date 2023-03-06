Conversation topics used in research by @NettaWeinstein

In the intial project, there are 4 conditions:

1. Training in Listening
2. Training in Speaking
3. Training in Listening-in-motion
4. No training

In study 2, trialing initially 3 conditions

```json
{
  "batchName": "study2Pretest",
  "treatmentFile": "projects/weinstein_listening/treatments.weinstein.yaml",
  "dispatchWait": 10,
  "useTreatments": [
    "weinstein_listener_speaker",
    "weinstein_speaker_speaker_control",
    "weinstein_no_training_control"
  ],
  "useIntroSequence": "cross_party_match",
  "platformConsent": "US",
  "consentAddendum": "projects/weinstein_listening/readingConsentAddendum.md",
  "launchDate": "1 Mar 2023 21:36:00 EST",
  "lastEntryDate": "2 Mar 2023 1:00:00 EST",
  "closeDate": "2 Mar 2023 1:30:00 EST"
}
```

Running actual trials with prolific participants:

```json
{
  "batchName": "study_2_20230302_prolific",
  "treatmentFile": "projects/weinstein_listening/treatments.weinstein.yaml",
  "dispatchWait": 10,
  "useTreatments": [
    "weinstein_listener_speaker",
    "weinstein_speaker_speaker_control",
    "weinstein_no_training_control"
  ],
  "useIntroSequence": "cross_party_match",
  "platformConsent": "US",
  "consentAddendum": "projects/weinstein_listening/readingConsentAddendum.md",
  "launchDate": "02 Mar 2023 14:00:00 EST",
  "lastEntryDate": "02 Mar 2023 14:30:00 EST",
  "closeDate": "02 Mar 2023 16:30:00 EST"
}
```

```json
{
  "batchName": "try_run",
  "treatmentFile": "projects/weinstein_listening/treatments.weinstein.yaml",
  "dispatchWait": 10,
  "useTreatments": [
    "weinstein_listener_speaker",
    "weinstein_speaker_speaker_control",
    "weinstein_no_training_control"
  ],
  "useIntroSequence": "cross_party_match",
  "platformConsent": "US",
  "consentAddendum": "projects/weinstein_listening/readingConsentAddendum.md",
  "launchDate": "06 Mar 2023 14:25:00 EST",
  "lastEntryDate": "06 Mar 2023 14:35:00 EST",
  "closeDate": "06 Mar 2023 16:30:00 EST"
}
```
