# TouchGrass Quest Lab 🌿
## A small prompt-based experiment with Gemma in Google AI Studio

**Hacktoberfest 2026 — Week 1 theme: “Touch Grass”**

TouchGrass Quest Lab explores whether an open-weight language model can generate short, safe, phone-free outdoor activities and revise them when the user's constraints change.

> **Scope note:** This repository documents a manual experiment conducted through Gemma in Google AI Studio. It is not a standalone application, does not run inference locally, and does not claim offline operation. Check the challenge rules or ask the organizers whether a prompt-and-evaluation artifact meets the “build something” requirement before treating this as an eligible submission.

## Research question

Can Gemma generate practical outdoor quests and adapt them when time, environment, or activity constraints change?

## Setup and reproducibility

- Interface: Google AI Studio
- Model family: Gemma
- Inference: hosted through Google AI Studio
- Runtime, model version, generation settings, and date/time should be added by the author if available from the session UI.
- No local model installation or application code is part of this experiment.

To reproduce it, open Google AI Studio, select a Gemma model, run the prompts in `prompts/`, and save the resulting outputs. Model versions and responses can change, so the recorded outputs are a snapshot rather than a guarantee of identical future results.

## Preliminary observations

- The generated quests included concrete observation tasks such as comparing leaf shapes and listening for natural sounds.
- The revision explained why some activities were changed to fit a shorter time window and a smaller garden.
- Some constraints were only partly reflected: the revised output did not explicitly restate the five-minute duration, and it assumed access to a plant and designated garden paths.
- The experiment does not establish that the quests improve wellbeing or that Gemma is more effective than a closed model. Those claims would require additional testing.

## Why open-weight AI matters here

Using an open-weight model family makes it possible for developers to explore model behavior and, in suitable setups, choose different deployment arrangements or adapt the model. This experiment used a hosted interface, however, so it did **not** demonstrate local privacy, offline use, or full control over the inference environment. Those would be separate experiments.

## Limitations and next steps

- This is a small qualitative experiment with very few prompts.
- There is no controlled comparison against another model.
- No formal scoring by multiple evaluators was performed.
- No real-world field test is claimed unless the author completes one and records what happened.
- A useful next step would be a small scripted evaluation or a simple user-facing prototype, if required by the challenge.

## Submission

Link to the DEV post here: ****.

Suggested tags: `#devchallenge` `#hf26challenge`
