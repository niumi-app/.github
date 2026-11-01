<!--
A promotion: head `development`, base `main`. Title: `release(<repo>): <yyyy-mm-dd> <summary>`.
This body becomes the merge commit's message on `main`: delete every comment before you open the PR.
-->

## Carries

<!-- Every task PR since the last promotion, one line each: #N and its title. `git log --oneline --first-parent origin/main..origin/development` lists them. -->

## Impact

- **Migrations:** none <!-- or each migration this release applies, and why the running release keeps working against it -->
- **Contract:** none <!-- or what changed, and the order: the contract's owner promotes before its consumers -->
- **After the deploy:** none <!-- or each one-off step, in order, and who runs it -->

## Release checks

<!-- On development's head (its short SHA): the repo's Definition of Done and its release checks (docs/workflow.md → Release), each with its summary line, run through `niumi heavy`. -->

## Approval

<!-- The owner's go, quoted with its date. -->

## Checklist

- [ ] Head `development`, base `main`; merged with a merge commit, never squashed or rebased, and `development` kept
- [ ] The repo's Definition of Done and release checks are green on `development`'s head
- [ ] Every migration is safe for the running release; a breaking one is a planned outage, not this promotion
- [ ] What this release needs is already in production: the contract's owner promoted first
- [ ] Every task PR it carries is listed under Carries
- [ ] Merged only on the owner's go, quoted under Approval
