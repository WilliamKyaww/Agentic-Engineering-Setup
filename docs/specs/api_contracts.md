# Interface and API Contracts

Delete this document if the project has no external or internal interface
contract worth governing.

## Status

- **State:** Draft
- **Version:** <Version>
- **Owner:** <Owner>

## Conventions

- <Protocol, encoding, authentication, versioning, and error conventions>

## Error shape

```json
{
  "code": "STABLE_MACHINE_CODE",
  "message": "Human-readable explanation",
  "details": {}
}
```

## Contract: <Operation>

- **Input:** <Schema>
- **Output:** <Schema>
- **Validation:** <Rules>
- **Authorisation:** <Rules>
- **Failure modes:** <Stable errors>
- **Idempotency:** <Behaviour>

## Compatibility policy

<How breaking changes are proposed, versioned, tested, and released.>
