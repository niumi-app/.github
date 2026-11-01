# niumi-app/.github

The organization's default files. GitHub uses them in every `niumi-app` repository that has none of its own.

- `.github/PULL_REQUEST_TEMPLATE.md`: the pull request template for every change.
- `.github/PULL_REQUEST_TEMPLATE/promotion.md`: a promotion, `development` into `main`. On the web, add `?template=promotion.md` to the compare page's address.

Agents read the text with `niumi pr template` (or `--promotion`) and pass it to `gh pr create --body-file`, since `gh` applies no template when the body is given.

Changes come as pull requests from the Niumi platform session.
