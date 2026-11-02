<!--
The Niumi pull request template, for every kind of change. A promotion (development → main) uses PULL_REQUEST_TEMPLATE/promotion.md.
Title: a Conventional Commit summary, `<type>(<scope>): <summary>`.
Fill every section; write "none" where nothing applies. Delete every comment before you open the PR.
Name another PR as "for #N", never "fixes", "closes" or "resolves #N": GitHub closes what those name.
-->

## What and why

<!-- First line: the change in one sentence. Then what changed, in short bullets. Then why: the ask, quoted with its date, or the record it carries out. -->

## Impact

- **Contract:** none <!-- or what changed, the SDK or contract regenerated, and each consumer with its PR; the contract's owner merges first -->
- **Schema:** none <!-- or the migration, and why the running release keeps working against it (expand and contract) -->
- **Screens:** none <!-- or the screens touched and the shots looked at; every word from the bg and en catalogs -->
- **Personal data, AI that talks to people, card data:** none <!-- or what the suite's compliance checklist asks here, and how this change meets it -->
- **After the merge:** none <!-- or each step someone takes after it: a restart, a vendoring, a docs commit, a one-off job -->

## Calls made

<!-- Each choice the brief or spec left open: what you chose, the options, and why. Link the decision record of a choice with lasting weight. -->

## Checks

<!-- On the head you pushed (its short SHA): each step of the repo's Definition of Done with its summary line (its gate, e2e, rehearsal and image runs through `niumi queue`, agent rules §2); the review's tier and verdict; what was not run, and why. -->

## Later

<!-- What goes to later: findings below the blocking bar and follow-ups, one line each, with their source. -->

## Checklist

- [ ] One task: one branch and one PR, with nothing unrelated in the diff
- [ ] The repo's Definition of Done is green on this head, its queued runs through `niumi queue`
- [ ] New and changed behaviour has tests beside its code
- [ ] Docs and rules match the change: this repo's in this PR, a shared one in niumi-docs
- [ ] Every decision made here is recorded, and nothing here breaks an accepted record
- [ ] No blocking finding is open; the rest is under Later
- [ ] No secret, credential or real data in the diff, this body or the output quoted

<!-- Tick a box only when it is true. A box left open says why on its line, after a dash. End the body with your session's attribution lines. -->
