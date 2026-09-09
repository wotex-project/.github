# WoTEx Community Health Repository Contract

This repository owns the default community health files and organization
profile for WoTEx repositories. Keep its policies concise, enforceable, and
consistent with the repository-specific files that override these defaults.

Do not add package source, release automation, or project-specific engineering
contracts here. Update default templates and their documentation together.

## Git authority

Automated agents must never configure, add, change, or remove a Git remote;
push; create a tag; publish; create equivalent remote state; or change
repository visibility. Only the human maintainer performs publication.

Local commits use the identity already configured by the contributor running
Git. Automated agents must never set or override Git identity; record an agent,
tool, or bot as an author, committer, or co-author; invent a contributor
identity; or remove attribution supplied by a human contributor.
