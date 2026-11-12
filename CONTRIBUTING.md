# Contributing

Thanks for taking part. This repository is run through VoltConnect, so a few things work
differently from an open GitHub project.

## Getting access

You can't ask for access on GitHub. Join the project's group in VoltConnect, link your GitHub
account, and ask to join there. Once you're accepted, GitHub sends you an invitation with
**write** access. Accept it within 7 days; if it expires, ask for it again in VoltConnect.

Your GitHub account needs two-factor authentication. The organisation requires it, and GitHub
removes anyone who turns it off.

## Picking a task

Tasks are this repository's issues. VoltConnect shows them with their labels:

| Label | Meaning |
| --- | --- |
| `level:beginner`, `level:intermediate`, `level:pro` | The experience the task needs |
| `scope:small`, `scope:medium`, `scope:large` | Roughly how big it is |
| `good first issue` | A good place to start |

Take a task in VoltConnect before you start, so two people don't do the same work. Taking it
assigns the issue to you on GitHub. If you can't finish, let it go in VoltConnect so someone else
can pick it up.

## Making a change

1. Create a branch from `main`, named after the issue, for example `42-fix-login-copy`.
2. Keep the change to that one task.
3. Open a pull request into `main` and fill in the template. Write `Closes #42` in it, so the task
   moves to "in review" and then "done" in VoltConnect.
4. A maintainer reviews it. Reply to comments by pushing more commits to the same branch.
5. A maintainer merges it once it's approved.

`main` is protected. Nobody can push to it directly, force-push it or delete it, and every pull
request needs a maintainer's approval. Release tags (`v*`) are created by maintainers only.

## Rules for this repository

- **No secrets.** Never commit passwords, API keys, tokens, private keys or `.env` files. If you
  commit one by mistake, tell a maintainer straight away; deleting it in a later commit doesn't
  remove it from the history.
- **No workflows.** GitHub Actions is turned off for the organisation, so files in
  `.github/workflows` never run. Pull requests that add them are closed.
- **Your own work.** Only submit work you have the right to share under this repository's licence.
  If you used generated code, say so in the pull request.
- **Be decent.** VoltConnect's community guidelines apply here as they do in the app. Report a
  problem through the project in VoltConnect.

## Reporting a security problem

Don't open a public issue. Report it to the maintainers through the project in VoltConnect, or use
GitHub's private vulnerability reporting if it's turned on for this repository.

## Leaving

Leave the project in VoltConnect at any time. Your GitHub access ends at the same moment. What you
contributed stays in the repository's history under its licence.
