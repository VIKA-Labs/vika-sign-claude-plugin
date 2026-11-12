# VIKA Sign for Claude

Connect Claude to your VIKA Sign organization to search and review agreements, contracts, acceptances, workflows, automation runs, and audit evidence. The plugin includes task-specific skills and connects to the VIKA Sign Remote MCP service over HTTPS. Every user authenticates with their own VIKA Sign account; the server resolves the organization from that authorization.

## Use it

Install the plugin from Claude's directory, connect the VIKA Sign connector, and ask Claude to find an agreement, explain contract risk, review obligations, compare versions, prepare a draft, or inspect evidence. You can also ask Claude to create or manage an automation. Review the proposed change and confirm before a write or an external action. Use the agreement cards and automation interface when Claude offers the interactive connector view.

## Data

The plugin sends your requests to `https://sign.vikasign.com/mcp`. Depending on the tool, the request can include search terms, identifiers, contract or envelope fields, recipient details, automation definitions, and document content you explicitly select for import or review. VIKA Sign returns authorized records and stores changes in your tenant according to your organization's retention, audit, and approval settings. OAuth credentials are handled by Claude and VIKA Sign; never place credentials, tokens, secrets, or tenant IDs in a prompt.

## Privacy and support

See the [VIKA Sign privacy policy](https://sign.vikasign.com/privacy.html), [terms](https://sign.vikasign.com/terms.html), [setup guide](https://sign.vikasign.com/connectors/claude), and [support](https://sign.vikasign.com/support).
