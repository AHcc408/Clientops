# ClientOps

ClientOps is an agent-native client-work command center for independent professionals. It keeps projects, delivery tasks, invoice drafts, and client follow-ups in one shared workspace.

## WebMCP tools

- `get_workspace_brief` — read-only work and cash-risk briefing
- `create_work_item` — add a delivery task
- `draft_follow_up` — prepares, never sends, a client follow-up
- `create_invoice_draft` — prepares, never sends or charges, an invoice
- `update_task_status` — records delivery progress

The app uses the browser's native `document.modelContext.registerTool()` API. When opened in a browser without WebMCP, the human UI remains fully functional and reports that WebMCP is unavailable.

## Run locally

This is a dependency-free static app. Serve `clientops/` using any static server, for example `npx serve clientops`.

## Hackathon submission description

ClientOps solves the fragmented client-work problem for freelancers, agencies, and independent developers. People and agents share the same operational workspace: agents can reliably retrieve structured context and prepare tasks, invoice drafts, and follow-ups, while humans retain approval for external or financial actions. WebMCP makes this reliable and inspectable, instead of requiring an agent to infer meaning from a visual dashboard or send actions through brittle UI automation.

## License

MIT
