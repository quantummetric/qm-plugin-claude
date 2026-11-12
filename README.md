# Quantum Metric for Claude Code and Claude

Analyze funnels, errors, friction and session replays in Quantum Metric to find and fix digital experience issues.

## Install

**Claude Code**

```
/plugin marketplace add https://github.com/quantummetric/qm-plugin-claude.git
/plugin install quantum-metric@quantum-metric
```

**Claude desktop and web:** go to Customize › Connectors, select + Add › Add custom connector, and enter `https://api.quantummetric.com/mcp`.

## Configure

The server uses Quantum Metric sign-in (OAuth). Every call runs as you, with your role, permissions, workspace and timezone. No token is created or stored.

| Setting | Value |
|---|---|
| Endpoint | `https://api.quantummetric.com/mcp` |
| Subscription | Chosen when you sign in |

## Skills

- `getting-started`: confirms the subscription, workspace and timezone, and fixes common connection problems
- `data-analysis`: answers funnel, conversion, error and trend questions with verified numbers
- `session-review`: explains what a user experienced in one or more sessions
- `session-reader` (agent): reads one long session and returns only the answer

## Support

support@quantummetric.com, or the [Quantum Metric support portal](https://thequad.quantummetric.com/).

## Privacy

[Quantum Metric Privacy Policy](https://www.quantummetric.com/legal/privacy-policy)

## Terms

[Quantum Metric Terms and Conditions](https://iam.quantummetric.com/terms-and-conditions)

## License

MIT
