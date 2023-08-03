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
  "treatments": [
    "weinstein_listener_speaker",
    "weinstein_speaker_speaker_control",
    "weinstein_no_training_control"
  ],
  "introSequence": "cross_party_match",
  "platformConsent": "US",
  "consentAddendum": "projects/weinstein_listening/readingConsentAddendum.md",
  "launchDate": "1 Mar 2023 21:36:00 EST"
}
```

Running actual trials with prolific participants:

```json
{
  "batchName": "study_2_20230302_prolific",
  "useData": false,
  "treatmentFile": "projects/weinstein_listening/treatments.weinstein.yaml",
  "dispatchWait": 10,
  "treatments": [
    "weinstein_listener_speaker",
    "weinstein_speaker_speaker_control",
    "weinstein_no_training_control"
  ],
  "introSequence": "cross_party_match",
  "platformConsent": "US",
  "consentAddendum": "projects/weinstein_listening/readingConsentAddendum.md",
  "launchDate": "02 Mar 2023 14:00:00 EST"
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

```json
{
  "batchName": "20230801_prolific_dem40_rep40",
  "useData": "true",
  "treatmentFile": "projects/weinstein_listening/treatments.weinstein.yaml",
  "dispatchWait": 15,
  "treatments": [
    "weinstein_listener_speaker",
    "weinstein_speaker_speaker_control",
    "weinstein_no_training_control"
  ],
  "introSequence": "cross_party_match",
  "platformConsent": "US",
  "consentAddendum": "projects/weinstein_listening/readingConsentAddendum.md",
  "launchDate": "01 Aug 2023 13:30:00 EDT",
  "embargoUntil": "01 Aug 2025 13:30:00 EDT",
  "videoStorageLocation": "deliberation-lab-recordings-weinstein",
  "dataRepos": [
    {
      "owner": "Watts-Lab",
      "repo": "deliberation-data-private",
      "branch": "main",
      "directory": "scienceData"
    },
    {
      "owner": "JamesPHoughton",
      "repo": "listening-study",
      "branch": "main",
      "directory": "data"
    }
  ]
}
```
