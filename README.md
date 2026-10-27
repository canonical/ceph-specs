# ceph-specs

Specifications for the Ceph team. Specs live in [`specs/`](specs).

## Writing a spec

1. Copy [`spec-template.md`](spec-template.md) to
   `specs/CE<NNN>-short-title.md`, using the next free number
   (e.g. `specs/CE042-rgw-multisite.md`).
2. Fill in the frontmatter (`index` must match the file name) and the
   sections. Keep it brief; there is no minimum length.
3. Open a pull request and list your reviewers in the frontmatter.

## Status

A spec moves through these states, recorded in the `status` field:

- `braindump`: early ideas, not ready for review
- `drafting`: being worked out and reviewed
- `approved`: accepted; open issues are resolved

The spec's history (changes, review discussion) is tracked in git and its
pull requests.
