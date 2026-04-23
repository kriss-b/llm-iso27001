# LLM ISO 27001

This repository is a complete, viable Information Security Management System (ISMS) aligned with **ISO 27001:2022**. It is designed to be cloned and immediately customised by your own LLM Agent (e.g. OpenAI Codex, Claude Code, OpenCode / Pi, or etc.) for any company seeking ISO 27001 certification or a structured approach to information security.

Everything is plain markdown, version-controlled with git, and intentionally kept free of tooling, build steps, or proprietary formats. The LLM can read it, understand it, modify it, and maintain it - preferably with the supervision of a human - even more preferably with a human having some level of ISO 27001 expertise.

---

## What's in here

A full ISMS documentation set: policies, procedures, risk assessment framework, incident management, a Statement of Applicability covering all 93 ISO 27001:2022 Annex A controls, and an annual management review template (among others). The placeholder company is **ACME CORP**. Every document follows the same structure and ends with a Changelog so nothing is ambiguous about ownership, approver, version, or history.

The `statement_of_applicability.md` is the master index. It maps every ISO 27001:2022 clause and Annex A control to its implementation status and the document that covers it. Start there to understand what exists and what gaps remain. The default status is intentionally 'not yet implemented' to force proactive review of all controls.

---

## How to use this with an LLM agent

Click **Use this template** on GitHub to create your own repository under **YOUR_GITHUB_USERNAME**, name it **my-company-isms**, then clone it locally:

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/my-company-isms.git
cd my-company-isms
ln -s AGENTS.md CLAUDE.md   # Claude Code only — auto-loads agent instructions
```

Then open a session with your LLM Agent of choice and give it context about your company. The more context, the better the output. For example:

> We are **[YOUR COMPANY NAME]**, you can find information about us on **[YOUR COMPANY WEBSITE]** and more generally on the internet. We operate from [your country]. Our tech stack is [cloud providers, key systems]. We are [remote-first / hybrid / office-based].
>
> 1. Replace ACME CORP with our company name across all documents.
> 2. Review the ISMS Policy (policies/isms_policy.md) — especially the context, scope, internal/external issues, and interested parties sections — rewrite them to reflect our actual situation, not just replace the company name.
> 3. Review the Statement of Applicability (statement_of_applicability.md) and flag any controls where our context changes the applicability or status.
> 4. Update roles and responsibilities with stakeholders found on the internet
> 5. Setup initial risks based on your understanding of our context
> 6. Setup vendor list and assessment based on our context 

From there, iterate. The LLM can update the SoA and the policies, refine the risk register, and maintain cross-references between documents as your ISMS evolves. It can also, why not if necessary, draft new policies. 

---

## Design principles

**One source of truth per topic.** Every control maps to one document. Cross-references use relative markdown links so they work in any markdown renderer and an agent can follow them.

**No redundancy.** Documents don't repeat each other. The SoA is the index; the policies are the detail. If something needs updating, there is exactly one place to update it.

**LLM-maintainable.** All documents are self-contained markdown with a standard structure. The LLM that reads the Changelog at the end of any file knows the owner, approver, version, and history without needing to parse free-form text.

**Git is the changelog.** Per-document changelog tables exist for human readability, but git history is the authoritative record. Don't fight it.

---


## Staying up to date with the template

If you cloned this repo to create your own ISMS, you can track upstream improvements over time — new policies, updated controls, structural refinements — and let an agent decide what is worth adopting.

**Add the template as a remote (one-time setup):**

```bash
git remote add upstream https://github.com/christophebourguignat/llm-iso27001.git
```

**When you want to check for updates:**

```bash
git fetch upstream
git diff HEAD..upstream/main > upstream_changes.diff
```

Then open a session with your LLM Agent and say something like:

> The file `upstream_changes.diff` contains changes made to the upstream ISMS template since I cloned it. Our company is [brief context reminder]. Please:
> 1. Summarise what has changed in the template (new policies, updated controls, structural improvements).
> 2. For each change, assess whether it is relevant to us given our context.
> 3. Propose concrete updates to our local ISMS where the upstream change adds value, adapting the content to our specific situation rather than applying it blindly.

The LLM should not merge blindly. Your instantiated ISMS has been customised for your company; upstream changes are suggestions, not patches. The diff gives the agent the raw material — your company context guides what gets adopted.

---

## What this is not

This is a LLM friendly template, not a certification. Achieving ISO 27001 certification requires an accredited external audit, evidence of the ISMS operating over time (logs, completed reviews, incident records), and demonstrated continual improvement. This repository gives you the documented framework. Running it is up to you and your LLM.
