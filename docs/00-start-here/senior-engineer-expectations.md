# Senior Engineer Expectations

A senior engineer is expected to solve technical problems while considering business context, team impact, long-term maintainability, and production risks.

## Core expectations

Senior engineers are expected to:

- Deliver reliable solutions
- Understand trade-offs
- Communicate clearly
- Own production outcomes
- Improve team practices
- Mentor other engineers
- Design maintainable systems
- Reduce unnecessary complexity
- Identify risks early
- Balance speed and quality

## Difference between middle and senior answers

A middle-level answer often explains how a tool works.

A senior-level answer explains:

- Why the tool is appropriate
- What alternatives exist
- What trade-offs are involved
- How the solution behaves in production
- How to test it
- How to monitor it
- How to evolve it safely

## Example

Question:

```text
How would you improve frontend performance?
```

Weak answer:

```text
I would use memoization and lazy loading.
```

Stronger senior-level answer:

```text
I would first measure the problem using performance profiling, Web Vitals, bundle analysis, and real-user monitoring. Then I would identify whether the bottleneck is rendering, network, JavaScript execution, data fetching, or assets. Based on that, I might use route-level code splitting, virtualization, caching, memoization, image optimization, or architectural changes. I would also verify the improvement with metrics, not assumptions.
```

## Key idea

Senior engineers are evaluated by judgment, not only knowledge.
