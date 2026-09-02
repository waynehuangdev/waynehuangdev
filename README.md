# Wayne Huang

**I automate the job nobody wanted to hire for.**

Ten years writing software, most recently on AI agents and agentic workflows. I build internal tools, document search, and integrations for companies too small to hire someone in-house — usually the process that's currently running on copy-paste and one person's patience.

[waynehuang.dev](https://waynehuang.dev) · [wayne@waynehuang.dev](mailto:wayne@waynehuang.dev)

---

### [Federal contract scanner](https://contract-scanner.waynehuang.dev)

Government IT contracts are filed under classification codes assigned by contracting officers, and those codes are frequently wrong. In one week's data, NAICS 541519 — "Other Computer Related Services" — was 60% of all notices and contained RF cables, UPS battery maintenance, Cisco switches, licence renewals, and a weapons storage system.

This reads the notices themselves and says which are actually services work, with a one-line reason citing the text. The clearest example it found: a notice that reads as a plausible data engagement, where the description reveals a sole-source award already intended for a named vendor and a fifteen-day window to *object*, not bid. No title or code carries that.

TypeScript on Cloudflare Workers. Fetching separated from scoring to live inside a 10-request/day API budget; scores cached per notice; 94 tests that need no network and no API key.

### [Email intake pipeline](https://intake.waynehuang.dev)

Customer inquiries arrive as email and come out as structured records with a drafted reply waiting for approval. Handles the messy cases — missing fields, forwarded chains, messages that aren't inquiries at all — and shows its confidence rather than hiding it.

---

Available for project work. If something in your week keeps getting done by hand, [tell me about it](mailto:wayne@waynehuang.dev).
