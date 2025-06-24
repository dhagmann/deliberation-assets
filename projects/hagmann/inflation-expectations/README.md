# Inflation Expectations Experiment

## Overview

This experiment studies how people form inflation expectations and how these expectations change through social discussion. Participants are asked to forecast inflation rates, discuss their reasoning with a partner, and then have the opportunity to revise their forecasts.

## Experiment Design

### Stage 1: Initial Forecast
- Participants provide their inflation forecast for the next 12 months
- Multiple choice options: <0%, 0-2%, 2-5%, 5-10%, >10%
- Includes explanation of inflation with concrete examples

### Stage 2: Information Sources
- Participants indicate what sources they use to form inflation expectations
- Multiple select options including: grocery prices, gas prices, rental prices, wage changes, news/media, personal experiences, economic data, other

### Stage 3: Discussion
- Participants are paired for a 5-minute text chat
- They discuss their inflation forecasts and reasoning
- Guidelines encourage respectful, constructive conversation

### Stage 4: Revision
- Participants indicate if their forecast changed after discussion
- Options: increased, decreased, or remained the same
- Open response question asking for detailed explanation of reasoning

### Stage 5: Demographics
- Age group, education level, economic familiarity
- Used for analysis of how different groups form expectations

## Participant Pairing Strategy

The experiment uses forecast-based pairing to ensure meaningful discussions:

### Forecast-Based Pairing (`inflationExpectations`)
- **Pairing Strategy**: Pairs participants with different inflation expectations
- **Position 0**: "Lower Inflation" (forecasts: <0%, 0-2%, 2-5%)
- **Position 1**: "Higher Inflation" (forecasts: 5-10%, >10%)
- **Research Question**: How do discussions between people with different inflation expectations affect forecast revisions?

This pairing strategy ensures that participants discuss inflation with someone who has a different perspective, potentially leading to more meaningful exchanges and greater forecast revisions.

## Research Questions

1. How do people form inflation expectations?
2. What information sources do they rely on?
3. How do social discussions influence inflation forecasts?
4. What factors lead to forecast revisions?
5. How do demographic characteristics relate to inflation expectations?
6. How do discussions between people with different inflation expectations affect forecast revisions?

## Files

- `inflation-expectations.treatments.yaml` - Main experiment configuration
- `welcome.md` - Introduction and overview
- `initial_forecast.md` - First forecast collection
- `information_sources.md` - Information source identification
- `pre_discussion_instructions.md` - Discussion preparation
- `discussion_prompt.md` - Chat discussion guidance
- `revised_forecast.md` - Post-discussion forecast change
- `revision_reason.md` - Explanation of revision reasoning
- `demographics.md` - Final demographic questions
- `inflation_forecast_survey.md` - Survey for initial forecast
- `information_sources_survey.md` - Survey for information sources
- `revised_forecast_survey.md` - Survey for forecast revision
- `revision_reason_survey.md` - Survey for revision reasoning
- `demographics_survey.md` - Survey for demographics
- `inflation-expectations.local.config.json` - Local testing configuration

## Implementation Notes

- Uses text chat for discussion (not video)
- 5-minute discussion duration
- Forecast-based pairing ensures discussions between people with different expectations
- Includes comprehensive instructions and examples
- Focuses on respectful, constructive dialogue
- Survey-based pairing uses `reference: survey.inflationForecast.result` with `isOneOf` comparator 