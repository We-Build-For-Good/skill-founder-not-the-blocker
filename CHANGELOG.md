# Changelog

## 1.1.0 (2026-10-20)

- Safety gap: deleting data, destructive migrations, force-pushes and credential revocation were not on the human-decision list, and 'silence equals authorization' applied to anything git-revertable. Added a fifth category for destructive or irreversible system changes; silence is never consent for them.
