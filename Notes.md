# Notes

## Question(s)

1. When a protocol gives you only an Etherscan link, what do you think should be your next step?

> You don't audit it. If the creator insists, then it is the proof that they don't want to be safer. You can charge them extra money to make the codebase more mature.

2. Should we review a codebase again?

> Maybe. We can always review codebases again. However, we need to timebox ourselves. We might not have enough time if we have alot of codebases to review.

## Solidity Fun Facts

- Binary shifting actually allows overflow

## Common Bugs/Exploits

Denial of Service (DoS)
- Denial of Service is an exploit that makes the contract unable to be used. It is usually related to block gas limit.
- Types of possible explots
  - Unbounded loop
  - Lack of gas due to operations
