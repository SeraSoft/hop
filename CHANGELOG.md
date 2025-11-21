# Hop - Serasoft LTS

This release train includes a few bugfixes, backported from Serasoft from the main branch to support branches of the official Hop repository.

Generally, official releases are never patched on the release branch, so we won't see any official `2.15.1`, `2.14.3` and so on. The release policy from the community has been, so far, "you take the latest minor release", like `2.15.0`, `2.16.0`, etc.

Unfortunately, as software evolves, regressions are always around the corner, so the codebase stability is not reliable for many clients.
Therefore, the underlying idea is to keep a few versions as LTS (Long Term Support) for those clients which stability is crucial.

# Changelogs

## Patch Release 2.16.1

- **[Issue 6008](https://github.com/apache/hop/issues/6008)**: [Bug]: Problem with duplicate field names in timeline after 'Split fields' step
