# Setup Instructions for Video Chat Test

## Quick Start

1. **Start the local server** (in your terminal):
   ```bash
   npx http-server --cors -a localhost -p 9090
   ```

2. **In your Empirica admin panel**, use this configuration:
   ```json
   {
     "batchName": "video_chat_test",
     "cdn": "local",
     "treatmentFile": "projects/video-chat-test/video-chat-test.treatments.yaml",
     "introSequence": "videoChatIntro",
     "treatments": ["videoChatTest"],
     "dispatchWait": 1,
     "checkAudio": true,
     "checkVideo": true
   }
   ```

   If the above does not work, try the following as it initializes all configurations:

   ```json
   {
  "batchName": "video_chat_test",
  "cdn": "local",
  "treatmentFile": "projects/hagmann/video-chat-test/video-chat-test.treatments.yaml",
  "customIdInstructions": "none",
  "platformConsent": "US",
  "consentAddendum": "none",
  "checkAudio": false,
  "checkVideo": false,
  "introSequence": "videoChatIntro",
  "treatments": [
    "videoChatTest"
  ],
  "payoffs": "equal",
  "knockdowns": "none",
  "dispatchWait": 1,
  "launchDate": "immediate",
  "centralPrereg": false,
  "preregRepos": [],
  "dataRepos": [],
  "videoStorage": "none",
  "exitCodes": {
    "complete": "VideoChatTestComplete",
    "error": "VideoChatTestError",
    "lobbyTimeout": "VideoChatTestTimeout",
    "failedEquipmentCheck": "VideoChatTestEquipmentFailed"
  }
   ``` 

## What this experiment does:

1. **Welcome Screen**: Introduces participants to the experiment
2. **Role Assignment**: Randomly assigns participants to "Speaker" or "Listener" roles
3. **Instructions**: Shows role-specific instructions to each participant
4. **Video Chat**: 3-minute video discussion between the two participants
5. **Feedback**: Simple question asking if the video chat worked properly

## Testing locally:

- You'll need 2 browser windows/tabs to test
- Each participant will need to allow camera and microphone access
- The experiment will automatically pair participants and start the discussion

## Files created:

- `welcome.md` - Welcome screen
- `speaker_instructions.md` - Instructions for Speaker role
- `listener_instructions.md` - Instructions for Listener role
- `discussion_prompt.md` - Shared prompt during video chat
- `feedback_question.md` - Post-chat feedback question
- `video-chat-test.treatments.yaml` - Experiment configuration
- `video-chat-test.local.config.json` - Local setup configuration 