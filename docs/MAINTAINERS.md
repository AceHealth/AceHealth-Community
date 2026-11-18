# Maintaining the Ace community

## Triage

Review new issues labelled `status: needs triage`. Confirm the type, ask for missing details with `status: needs information`, and link duplicates before closing them. Remove the previous status label when changing stage; keep exactly one status label per open issue.

For accepted feature requests, use `status: under consideration`, then `status: planned`, then `status: in progress`. Do not infer a public commitment from internal plans. When an item reaches users, link the release, apply `status: shipped`, and close it as completed. Close rejected or duplicate items as not planned and explain why. Use `resolution: duplicate` or `resolution: not planned` as appropriate.

For bugs, confirm reproduction before marking planned or in progress. Apply `status: shipped` only when a fix is released, then link the release and close the issue.

Q&A is for usage questions. Announcements is for team updates. General and Show and tell are for community conversation. Ideas can host early brainstorming; move actionable requests to Issues and link both conversations so there is one tracked request.

## Publish release notes

1. Verify the app version, availability, and user-visible changes against the actual release.
2. Draft a GitHub Release using `docs/RELEASE_TEMPLATE.md`. Use a community tag such as `ace-v1.2.0`; do not imply that the tag contains application source.
3. Review the draft, remove empty sections, and publish when the app release is available. Mark beta releases as pre-releases.
4. Link the release from shipped issues and post an Announcements discussion if it warrants a separate conversation. Keep the release itself as the canonical notes.

## Optional GitHub Projects board

The current setup uses status labels and ROADMAP.md links and is usable without a board. Creating an organization Project requires GitHub Projects authorization; the setup token did not have `read:project` or `project` access.

Once authorized, create a **public** organization Project named **Ace Roadmap**, link it to this repository, and add a board grouped by Status: Under consideration, Planned, In progress, Shipped. Add an intake view for Needs triage and Needs information. Enable auto-add for open issues from `AceHealth/AceHealth-Community` and configure the built-in closed-item workflow. Keep board status aligned with the issue labels; no custom synchronization workflow is installed.

Confirm that the Project is public before linking it from README.md and ROADMAP.md. Do not import private application issues or internal planning notes. Add confirmed public commitments only.

## Community operations

Pin the welcome discussion through its discussion menu. Keep Q&A in answerable format and Announcements restricted to maintainer-created posts. Review moderation reports and accidentally posted private information promptly. Do not add automatic stale-issue closure or promise response deadlines without agreeing a support policy.
