# Phoenix desktop app: privacy policy

Last updated: 18 November 2026

Phoenix is a desktop app for macOS used by a development team. It runs on each person's own Mac. There is no Phoenix server: the publisher of Phoenix receives no data from the app.

## What Phoenix accesses

When you sign in, Phoenix asks the service (Atlassian Jira, GitLab, Google) for permission to read data on your behalf. Phoenix then shows that data in the app on your Mac:

- Jira: projects, issues, comments, boards, sprints, and the profiles of people on your site. Read only.
- GitLab: projects, merge requests, pipelines, issues, commits, branches and releases you can see. Read only.
- Google: calendar, Gmail (read only) and Drive, only for the sections you turn on.

Phoenix can only see what your own account can see, and only with the permissions you approved.

## What Phoenix stores, and where

Everything stays on your Mac:

- Sign-in tokens are kept encrypted. The encryption key is in your macOS keychain.
- Your settings (which sections are on, your saved views and filters, your name and email from the service) are kept in `~/Library/Application Support/Phoenix POC`.
- Data from the services is held in memory while the app runs and is not written to disk or kept longer than needed to show it.

Phoenix does not send your data to the publisher or to any third party, does not use analytics or tracking, and does not sell or share data.

## Removing access

Sign out in Phoenix (Settings > Accounts) to delete the stored tokens on your Mac. You can also revoke Phoenix's access at any time in your account settings: Atlassian (id.atlassian.com > Connected apps), GitLab (User settings > Applications), Google (myaccount.google.com > Security > Third-party connections).

## Contact

Questions: the Phoenix publisher, Haykaz Petrosyan, through the team's usual channels.
