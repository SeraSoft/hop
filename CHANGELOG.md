# Hop - Serasoft LTS

This release train includes a few bugfixes, backported from Serasoft from the main branch to support branches of the official Hop repository.

Generally, official releases are never patched on the release branch, so we won't see any official `2.15.1`, `2.14.3` and so on. The release policy from the community has been, so far, "you take the latest minor release", like `2.15.0`, `2.16.0`, etc.

Unfortunately, as software evolves, regressions are always around the corner, so the codebase stability is not reliable for many clients.
Therefore, the underlying idea is to keep a few versions as LTS (Long Term Support) for those clients which stability is crucial.

# Changelogs

## Patch Release 2.15.1

- **[Issue 5642](https://github.com/apache/hop/issues/5642)**: Attachments are not sent in Mail Action for Workflow
- **[Issue 5544](https://github.com/apache/hop/issues/5544)**: Mail Transform - email output field not selectable in subsequent transforms
- **[Issue 5663](https://github.com/apache/hop/issues/5663)**: Mail Action - empty attachment
- **[Issue 5664](https://github.com/apache/hop/issues/5664)**: Mail Transform - Validation failed for ZIP filename even if the name is not empty
- **[Issue 5660](https://github.com/apache/hop/issues/5660)**: [Feature] Merge diff "changed" fields enhancement. Please notice that features are not bound to be part of patch releases like this; however, since the [next bugfix](https://github.com/apache/hop/issues/5694) backport depends on the code in this commit, we need to bring this in.
- **[Issue 5694](https://github.com/apache/hop/issues/5694)**: Merge rows transform has fields mixed up
- **[Issue 5743](https://github.com/apache/hop/issues/5743)**: Auto save before execution does not work
