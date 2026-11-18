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

## Maintain the wiki

The public documentation lives at https://github.com/AceHealth/AceHealth-Community/wiki. Edit it in GitHub or clone `https://github.com/AceHealth/AceHealth-Community.wiki.git` to work locally. Wiki history is separate from this repository.

The Wiki Roadmap page is the canonical public roadmap. Keep direction summaries there and detailed community requests in Issues. Link a tracked issue from the relevant roadmap entry when one exists, and update its label when its stage changes. Only mark an item shipped once release availability is confirmed and link the release notes. Do not publish internal blockers, provisional prices, or unverified availability claims.

Keep Home and the sidebar links current when adding pages. Keep release entries in GitHub Releases and link to them from the wiki rather than copying the notes. A GitHub Projects board is optional; the wiki and labels do not depend on Projects authorization.

## Community operations

Pin the welcome discussion through its discussion menu. Keep Q&A in answerable format and Announcements restricted to maintainer-created posts. Review moderation reports and accidentally posted private information promptly. Do not add automatic stale-issue closure or promise response deadlines without agreeing a support policy.
