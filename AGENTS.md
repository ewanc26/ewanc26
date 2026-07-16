# AGENTS.md

Guidance for agents working on the `ewanc26` GitHub profile repository.

## Scope

The root `README.md` is the product: GitHub renders it on the account profile. It presents a bilingual Gaelic/English introduction, live GitHub and AT Protocol badges, grouped project tables, tools/technologies, infrastructure principles, current work, and contact/support links. There is no application source or build system.

## Rules

- Keep the voice personal, concise, and factual. Do not invent biography, affiliations, metrics, or project status.
- Preserve working links, image alt text, and readable rendering in both light and dark GitHub themes.
- Treat externally generated badges/cards as third-party dependencies; use stable HTTPS endpoints and do not embed secrets in query strings.
- Keep HTML within GitHub's supported Markdown subset.
- Keep the hand-maintained project catalogue, counts, PDS label, current-work list, and canonical/archived links synchronized with the repositories they describe.

## Validation

Review the rendered Markdown structure, check every link and image target, inspect raw HTML balance, and verify that private contact details or tokens are absent. Changes need no build, but they do need visual review at desktop and narrow widths. Keep the commit limited to profile content and assets.
