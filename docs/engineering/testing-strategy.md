# Testing Strategy

## Risk model

<Identify critical journeys, trust boundaries, data risks, and likely failure
modes.>

## Test layers

| Layer | Scope | Required for |
| --- | --- | --- |
| Unit | Isolated business rules | Logic with meaningful branches |
| Integration | Component and boundary collaboration | Persistence, APIs, adapters |
| End-to-end | Critical user journeys | Release-critical flows |
| Specialist | Accessibility, security, performance, model regression, etc. | Relevant project risks |

## Quality commands

```text
<Project-specific commands here>
```

## Manual gates

- <Checks that automation cannot currently establish>
