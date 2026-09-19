# Landing Archive Community Store

## Permanent identity

For this repository, use only:

- Git author/committer name and GitHub account: `Proof-of-Pizza21`.
- Git author/committer email: `259956083+Proof-of-Pizza21@users.noreply.github.com`.

This instruction overrides any different identity inherited from a parent
directory or global configuration. Before commits, tags, and publications,
verify local Git configuration and the effective author and committer identities.
Before publishing, also verify the authenticated GitHub account. Do not modify
signing keys without verifying that they belong to the account.

## Privacy

The user's real first and last names must not appear in files, versioned paths,
metadata, commits, tags, releases, or artifacts. The only permitted public identity
is the one above. Before each push, check hidden files, selected content, and the
entire history to be published.

Do not include personal test URLs, website archives, credentials, logs, local
paths, or device data. The package data directory contains only `.gitkeep`; data
created during use stays on the Umbrel device.

## Package

The store identifier is `proof-of-pizza21`; the app identifier is
`proof-of-pizza21-landing-archive`. Keep them stable after the first installation.
The initial preview targets `linux/amd64` and validation on umbrelOS 1.7.4.
Use only published and tested images with a verified digest. Do not claim device
tests were completed unless they actually were.

Keep `LICENSE-PLAYWRIGHT` alongside the seccomp profile derived from Playwright.
Umbrel generates `seccomp-profile.json` from the template during installation;
do not commit that generated file.
