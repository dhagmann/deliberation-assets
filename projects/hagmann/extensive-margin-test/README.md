# Extensive Margin Experiment

This experiment is designed to study how the "extensive margin of disagreement"—that is, the choice to engage or not engage in a conversation with someone who holds opposing views—is affected by different incentives and constraints. It explores how these initial conditions impact participants' feelings about the conversation and their behavior during it.

## Experimental Design

The core of the experiment investigates how different choice architectures influence a participant's willingness to engage in a persuasive conversation and their subsequent emotional and behavioral responses.

Participants are first surveyed on a contentious issue (mandatory waiting periods for abortions) to establish their position. They are then matched with a participant who holds the opposing view. The primary experimental manipulation involves randomly assigning pairs to one of six conditions, which vary on two axes: the choice to participate and the goal of the interaction.

### Key Research Questions
- How does offering a choice to participate in a disagreeable conversation affect engagement rates?
- How does a monetary bonus for participation influence this choice?
- How does assigning a persuasive goal (i.e., to change the other person's mind) versus a simple conversational goal affect participants' feelings and behavior?

### Treatments (Conditions)
The experiment uses a 3x2 design, resulting in six distinct treatments:

1.  **No Choice**: Participants are required to have the conversation.
    - `No_Choice_0`: Participant in group 0 (opposes waiting periods) is tasked with persuading their partner.
    - `No_Choice_1`: Participant in group 1 (favors waiting periods) is tasked with persuading their partner.

2.  **Volunteer Choice**: Participants are given the option to have the conversation.
    - `Choice_0`: Persuasion goal assigned to group 0 if they opt in.
    - `Choice_1`: Persuasion goal assigned to group 1 if they opt in.

3.  **Bonus Choice**: Participants are offered a $1.00 bonus to have the conversation.
    - `Bonus_Choice_0`: Persuasion goal assigned to group 0 if they opt in.
    - `Bonus_Choice_1`: Persuasion goal assigned to group 1 if they opt in.

## Key Metrics

The experiment measures several outcomes:

- **Willingness to Engage**: The binary choice to participate or not in the `Choice` and `Bonus_Choice` conditions.
- **Change in Beliefs**: The primary behavioral metric is the change in a participant's estimate of the percentage of women who regret having an abortion, measured before and after the conversation.
- **Anticipated Affect**: Before the conversation, participants are asked how pleasant, annoyed, and angry they *imagine* the conversation will be.
- **Experienced Affect**: After the conversation, participants are asked how pleasant, annoyed, and angry the conversation *was*.

## Experiment Flow

The experiment proceeds through a series of distinct stages, each corresponding to specific files in this directory.

1.  **Introduction & Pre-Questions (`introSequence`)**
    - `welcome.md`: A simple welcome message.
    - `pre_question.md`: Introduces the topic.
    - `missouri_abortion_survey.md`: The core survey that categorizes participants into one of two groups: **Oppose** (`position: 0`) or **Favor** (`position: 1`).
    - `regret_bonus_survey.md`: Captures the participant's initial estimate of the "regret percentage," which serves as the baseline for the primary behavioral metric.

2.  **Choice Prompt (`ChoicePrompt` stage)**
    - Participants are shown one of three prompts based on their assigned treatment, informing them about the upcoming chat.
    - `no_choice.md`: For `No_Choice` treatments.
    - `volunteer_choice.md`: For `Choice` treatments, asks for a Yes/No response.
    - `bonus_choice.md`: For `Bonus_Choice` treatments, asks for a Yes/No response.

3.  **Imagined Conversation Survey (`ImaginedConversation` stage)**
    - Before the chat, participants are asked to imagine what it will be like.
    - `imagined_intro.md`: Introduces the set of questions.
    - `imagined_pleasant.md`: Asks about anticipated pleasantness.
    - `imagined_annoyed.md`: Asks about anticipated annoyance.
    - `imagined_angry.md`: Asks about anticipated anger.

4.  **Goal Assignment (`GoalPrompt` stage)**
    - Just before the chat, participants receive their goal for the conversation. This is determined by their assigned treatment (e.g., `No_Choice_0`) and their group position.
    - `prompt_persuade.md`: Shown to the participant tasked with persuading their partner.
    - `prompt_reminder.md`: Shown to the other participant.

5.  **Live Chat (`Discussion` stage)**
    - Participants engage in a 5-minute, text-based chat with their partner.
    - This stage is conditional for the `Choice` and `Bonus_Choice` treatments, only running if the participant agreed to participate.

6.  **Post-Chat Survey (`PostChatSurvey` stage)**
    - Immediately after the chat, participants answer questions about their experience and have a chance to update their initial estimate.
    - `post_chat_revise_estimate.md`: Prompts for the revised regret percentage.
    - `post_chat_pleasant.md`: Asks about experienced pleasantness.
    - `post_chat_annoyed.md`: Asks about experienced annoyance.
    - `post_chat_angry.md`: Asks about experienced anger.

7.  **Demographics (`Demographics` stage)**
    - The final stage collects standard demographic information.
    - `demographics_intro.md`: Introduces the section.
    - `demographics_gender.md`
    - `demographics_age.md`
    - `demographics_ethnicity.md`
    - `demographics_education.md`
    - `demographics_politics.md`
    - `demographics_comments.md`: An optional open-ended comments box.

---
This structure is defined in `extensive-margin.treatments.yaml` and run via the settings in `extensive-margin.local.config.json`. 