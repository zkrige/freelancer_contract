# Freelance Software Development Contract

The software development contract I use with clients, published for other freelancers to use.

If you have suggestions, improvements, or spot a mistake, please submit a PR.

**NB: Use this at your own risk. I'm sure there are problems or loopholes. Don't blame me if it doesn't cover you.**

## Structure

The contract is modular. Three pieces, two documents:

| File | What it is | Changes per project? |
|---|---|---|
| [`standard-terms.md`](standard-terms.md) | Standing legal terms. Same for every client, same model as website terms of service. | No |
| [`project-terms.md`](project-terms.md) | The short document the client signs. Names the parties, states the project type, incorporates the Standard Terms by reference. | Yes |
| Schedules 1 to 3, inside `project-terms.md` | Every project variable: fees, rates, payment dates, scope, deliverables, time periods. | Yes |

The Standard Terms contain no numbers and no project detail. Every variable is a defined term pointing at a Schedule, so a rate change is a one-cell edit rather than a hunt through the body text.

## How to use it

1. Publish `standard-terms.md` somewhere stable (your website, a public repo) and keep the version number in the heading.
2. Copy `project-terms.md` per project, fill in every `[...]` placeholder, delete the rows that do not apply.
3. Point clause 3.1 at the URL of the Standard Terms version you published, or attach that version as an annexure.
4. Send the client the Project Terms to sign. Signing them binds them to the Standard Terms as well.

Clause 3.5 pins the project to the version of the Standard Terms named at signature, so publishing a new version never retroactively changes a live contract.

Why split it: clients do not want to get caught up in the fine print, which means lawyers and delays. They sign off on the essentials (scope, price, dates) while the standing terms sit behind a reference.

## Scope changes

Changes to a Fixed Scope Project go through a Change Order (clause 6 of the Standard Terms), which amends the Schedules. Do not edit a signed Schedule in place.

## History

Version 1 was a single `contract.md`. It was replaced by the modular structure above, addressing issues [#2](https://github.com/zkrige/freelancer_contract/issues/2), [#3](https://github.com/zkrige/freelancer_contract/issues/3) and [#4](https://github.com/zkrige/freelancer_contract/issues/4). The old file is in the git history at commit `7909e1d`.
