

# Self-Consistency

## Summary

Self‑Consistency builds on Chain of Thought (CoT) by prompting the model multiple times with the same task (using CoT), then selecting the most common answer across those responses. This consensus-based approach improves accuracy and reliability.  

## Example use case

At Thai Life Insurance, you want to assess whether a customer email about claim submission should be classified as “Urgent” or “Not Urgent”. Classification mistakes could delay important claims, so consistency matters.

## Prompt

**NOTE:** Repeat running this prompt in 3 different chat sessions

```
Classify the following customer email as "Urgent" or "Not Urgent." Think step by step:

"I urgently need to submit a death claim for my father. Please guide me quickly."

Classification:
```

## Why This Matters:
- More reliable decisions: Especially for sensitive matters like claims, where misclassification could delay critical support.
- Clear logic: Trainees can see how reasoning varies and how consensus improves consistency.
- Easy to practice: You can run prompts live in Copilot Chat and have attendees vote on the best classification.