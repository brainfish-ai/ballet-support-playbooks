# Ballet Support Playbooks

Support triage, summaries and reply drafting for Zendesk, Freshdesk and more. One click into Ballet.

Built for support leads, CX ops and anyone running a helpdesk. Every template here imports into [Ballet](https://ballet.dev), the agent operations platform for building, running and observing deterministic workflows, with one click.

[![Validate](https://github.com/brainfish-ai/ballet-support-playbooks/actions/workflows/validate.yml/badge.svg)](https://github.com/brainfish-ai/ballet-support-playbooks/actions/workflows/validate.yml)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Templates

<!-- templates:start -->

### Support

| Template | What it does | Trigger | Import |
|---|---|---|---|
| [Freshdesk Ticket Summary](templates/freshdesk-ticket-summary) | Summarise each new Freshdesk ticket in three bullets and add it as a private note for the agent who picks it up. | Freshdesk webhook (ticket created) | [Import](https://app.ballet.dev/import?repo=brainfish-ai/ballet-support-playbooks&path=templates/freshdesk-ticket-summary&ref=main) |
| [Support Reply Drafter](templates/support-reply-drafter) | Paste a customer message and get a polite, source-aware draft reply to review and send. | Manual run | [Import](https://app.ballet.dev/import?repo=brainfish-ai/ballet-support-playbooks&path=templates/support-reply-drafter&ref=main) |
| [Zendesk Ticket Triage](templates/zendesk-ticket-triage) | Classify every new Zendesk ticket with an LLM and write the priority and tags back as an internal note. | Zendesk webhook (ticket created) | [Import](https://app.ballet.dev/import?repo=brainfish-ai/ballet-support-playbooks&path=templates/zendesk-ticket-triage&ref=main) |

<!-- templates:end -->

## How import works

1. Click **Import** next to a template.
2. Sign in or create a Ballet workspace. Ballet fetches the template from this repository, pinned to an exact commit.
3. Review the steps and code on the preview screen, then confirm.
4. Add the listed secrets and publish.

Imported playbooks always start unpublished with triggers off, and secrets are never part of a template.

## More templates

This repository is one focused slice of [brainfish-ai/ballet-templates](https://github.com/brainfish-ai/ballet-templates), which holds every Ballet template. Other collections:

- [ballet-sales-playbooks](https://github.com/brainfish-ai/ballet-sales-playbooks): Lead enrichment, scoring and Slack alerts for Salesforce and web forms. One click into Ballet.
- [ballet-ops-playbooks](https://github.com/brainfish-ai/ballet-ops-playbooks): Signed webhooks, scheduled digests and issue triage with retries and observability. One click into Ballet.
- [ballet-mcp-playbooks](https://github.com/brainfish-ai/ballet-mcp-playbooks): Agent workflows that call MCP servers such as Linear and Slack. One click into Ballet.

## Contributing

This repository is generated from [brainfish-ai/ballet-templates](https://github.com/brainfish-ai/ballet-templates). Please open template pull requests there so every collection stays in sync. Issues are welcome here.

## License

[MIT](LICENSE)
