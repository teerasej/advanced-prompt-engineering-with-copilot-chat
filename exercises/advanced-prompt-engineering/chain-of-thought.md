
# Chain of Thought

## Summary

Ask Copilot to think step by step before giving an answer.

## Example use case

Break down complex queries—e.g., calculating returns or coverage details.

## Prompt

> forcing chain of thought

```
A customer has a 20,000 THB premium with a 5 % annual return.  
How much will it be worth in 3 years?  
Let’s think step-by-step:
```

> Chain of thought with few-shot

```
Q: A customer has a 20,000 THB premium growing 5% per year for 3 years.
Step 1: Year 1 = 20,000 × 1.05 = 21,000 THB
Step 2: Year 2 = 21,000 × 1.05 = 22,050 THB
Step 3: Year 3 = 22,050 × 1.05 = 23,152.50 THB
Answer: After 3 years, it's about 23,152.50 THB.

Now, here’s a similar one for you to solve:
Q: [Your own scenario…]
A:
```