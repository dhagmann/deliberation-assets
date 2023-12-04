Project to assess the impact of age and gender on talk-time balance

## Intro steps

- Answer a panel of yes/no questions
- Demographic survey

## Dispatch

- ideally, get partnered with someone who disagrees with you on an issue
- but initially, just get paired and given a random topic

## Game

#### Stage 1

Attitude dimensions
Asked to write arguments about your position
How compelling are these arguments?
Asked to write arguments against your position
How compelling are these arguments?
Tolerance for people who disagree
How much do you think you would enjoy discussing this issue with someone else?

#### Stage 2: Discussion

Conversation

1. Hello
2. Open discussion
3. Joint policy writing

## Post

Ask position again
How much do you support the statement you wrote? (behavioral)
Write arguments about your position
How compelling are these arguments?
Write arguments against your position
How compelling are these arguments?
Tolerance for people who disagree
Feeling heard
Willingness to have another discussion (behavioral)

## Inferred DVs

- Talk time balance

Start with a baseline, no interventions, describe:

- effect of age, gender, race on outcomes

## Demo Config

```json
{
  "batchName": "demo",
  "preregister": "false",
  "treatmentFile": "projects/css_lab/treatments.yaml",
  "dispatchWait": 1,
  "introSequence": "base_sequence",
  "treatments": ["baseline"],
  "cdn": "local",
  "platformConsent": "US",
  "videoStorageLocation": "deliberation-lab-recordings-test",
  "dataRepos": [
    {
      "owner": "Watts-Lab",
      "repo": "deliberation-data-test",
      "branch": "main",
      "directory": "demo"
    }
  ]
}
```
