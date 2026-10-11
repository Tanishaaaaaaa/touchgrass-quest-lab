# Qualitative evaluation

This is a small, informal review of the outputs. Ratings are not benchmark scores and should not be presented as objective performance measurements.

## Rubric

- **Relevance:** Does the quest fit the requested activity?
- **Actionability:** Are the tasks concrete and understandable?
- **Constraint adherence:** Does the output respect time, setting, and other limits?
- **Safety:** Does it avoid obvious unsafe or intrusive behavior?
- **Phone-free design:** Can the quest be read first and completed without using the phone?

## Findings

| Scenario | What worked | What was weaker |
|---|---|---|
| Concrete Jungle Safari (10 minutes, mindful walking requested) | Concrete observations; simple safety reminder; phone use deferred until afterward | Output was more nature exploration than mindful walking; no explicit duration |
| Urban Leaf Detective (30 minutes, gardening/plant observation) | Specific leaf and plant observations; simple instructions | Mostly observation rather than gardening; no explicit duration |
| Garden Glimpse (5 minutes, no touching, public garden) | Adapted tasks to a smaller setting; explained revisions; safer setting-specific reminder | Did not explicitly repeat the five-minute limit; assumed a plant and garden access |

## Preliminary conclusion

In these examples, Gemma produced accessible outdoor observation activities and gave plausible explanations when asked to revise a quest. The examples also show that relevant output is not the same as full constraint adherence: the model did not consistently make the requested time limit explicit, and the gardening request became plant observation.

## What this experiment cannot show

- It cannot establish that the model is consistently reliable.
- It cannot show that the activity improves mental health or wellbeing.
- It cannot demonstrate offline inference or local data privacy.
- It cannot show that Gemma outperforms a closed model.
- It cannot establish challenge eligibility on its own.

## Next experiment

Repeat each scenario more than once and compare the results against the same rubric. If time permits, ask another person to rate the outputs without seeing which prompt produced them, and conduct a real outdoor trial before making claims about usability.
