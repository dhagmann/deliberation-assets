```json
{
  "batchName": "initial_demo",
  "treatmentFile": "projects/exaptation/exaptation_lego_pilot_4.treatments.yaml",
  "dispatchWait": 1,
  "treatments": ["schema"],
  "videoStorageLocation": "none",
  "exitCodeStem": "demo",
  "preregister": false,
  "cdn": "local",
  "dataRepos": [
    {
      "owner": "Watts-Lab",
      "repo": "deliberation-data-test",
      "branch": "main",
      "directory": "exaptation"
    }
  ]
}
```

```json
{
  "batchName": "initial_demo",
  "treatmentFile": "projects/exaptation/exaptation_lego_pilot_4.treatments.yaml",
  "dispatchWait": 1,
  "treatments": ["schema"],
  "videoStorageLocation": "deliberation-lab-recordings-test",
  "exitCodeStem": "demo",
  "preregister": false,
  "cdn": "prod",
  "dataRepos": [
    {
      "owner": "Watts-Lab",
      "repo": "deliberation-data-test",
      "branch": "main",
      "directory": "exaptation"
    }
  ]
}
```

```json
{
  "batchName": "initial_demo",
  "treatmentFile": "projects/exaptation/exaptation_lego_pilot.treatments.yaml",
  "dispatchWait": 1,
  "treatments": ["four_stage"],
  "videoStorageLocation": "none",
  "exitCodeStem": "demo",
  "preregister": false,
  "cdn": "local",
  "dataRepos": [
    {
      "owner": "Watts-Lab",
      "repo": "deliberation-data-test",
      "branch": "main",
      "directory": "exaptation"
    }
  ]
}
```

```json
{
  "batchName": "initial_demo",
  "treatmentFile": "projects/exaptation/exaptation_lego_pilot.treatments.yaml",
  "dispatchWait": 1,
  "treatments": ["four_stage"],
  "videoStorageLocation": "deliberation-lab-recordings-test",
  "exitCodeStem": "demo",
  "preregister": false,
  "cdn": "prod",
  "dataRepos": [
    {
      "owner": "Watts-Lab",
      "repo": "deliberation-data-test",
      "branch": "main",
      "directory": "exaptation"
    }
  ]
}
```

```json
{
  "batchName": "initial_demo",
  "treatmentFile": "projects/exaptation/exaptation_pilot.treatments.yaml",
  "dispatchWait": 1,
  "treatments": ["new_name_lineup"],
  "videoStorageLocation": "none",
  "exitCodeStem": "demo",
  "preregister": false,
  "cdn": "prod",
  "checkAudio": false,
  "checkVideo": false,
  "dataRepos": [
    {
      "owner": "Watts-Lab",
      "repo": "deliberation-data-test",
      "branch": "main",
      "directory": "exaptation"
    }
  ]
}
```

### Prestudy:

- have people rate the similarity of images

### Manipulate:

- do they have a discussion
- in the discussion, do they work to develop a naming scheme

- in the initial labeling and recall stages, do they do the exercise together, or do it individually?

### Measurement Options:

- show everyone the same image and they have 3 tries to type the same name for it, and we show them each others labels between

- show everyone an image and they have to pick the same name for it from a multiple choice set of options in one try (doesn't work as well to make use of the shared scheme)

- one person is the "labeler" and they send a label for an image, then we show that word to the other people in the group and they have to guess which image it comes from.

- manipulate the label, to choose something different, ie, so they have a shared schema but they can't make use of it.

- put them back in a call, and one person is the labeler has to describe the image they see so that others can pick it out of a lineup

- ask people how well they thought they did before we reveal the result, and see if the discusion makes them think they did better

{
"batchName": "initial_demo",
"treatmentFile": "projects/exaptation/exaptation_lego_pilot_3.treatments.yaml",
"dispatchWait": 1,
"treatments": [
"schema"
],
"videoStorageLocation": "deliberation-lab-recordings-test",
"exitCodeStem": "demo",
"preregister": false,
"cdn": "prod",
"dataRepos": [
{
"owner": "Watts-Lab",
"repo": "deliberation-data-test",
"branch": "main",
"directory": "exaptation"
}
]
}
