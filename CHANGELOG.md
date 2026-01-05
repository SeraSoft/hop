# Hop - Serasoft LTS

This release train includes a few bugfixes, backported from Serasoft from the main branch to support branches of the official Hop repository.

Generally, official releases are never patched on the release branch, so we won't see any official `2.15.1`, `2.14.3` and so on. The release policy from the community has been, so far, "you take the latest minor release", like `2.15.0`, `2.16.0`, etc.

Unfortunately, as software evolves, regressions are always around the corner, so the codebase stability is not reliable for many clients.
Therefore, the underlying idea is to keep a few versions as LTS (Long Term Support) for those clients which stability is crucial.

# Changelogs

## Path Release 2.16.2

- **[Issue 6274](https://github.com/apache/hop/issues/6274)** [BUg] MinIO plugin: MinIO part size parameter resolved from wrong variable
- **[Issue 6071](https://github.com/apache/hop/issues/6071)** [BUg] Get File Names don't list files in subfolder for MinIO
- **[Issue 6265](https://github.com/apache/hop/issues/6265)** Performance issue: Filter Rows step slower in Apache Hop compared to Pentaho Kettle
- **[Issue 6231](https://github.com/apache/hop/issues/6231)** [Bug]: Move files action does not add destination filenames to result + code cleanup
- **[Issue 6102](https://github.com/apache/hop/issues/6102)** [Bug]: Simple Evaluation: string comparison with null always return success
- **[Issue 6200](https://github.com/apache/hop/issues/6200)** [Bug]: Fixed layout of the MessageBox
- **[Issue 5225](https://github.com/apache/hop/issues/5225)** [Bug]: Cannot wire Workflow Executor results rows hop to next transform
- **[Issue 6060](https://github.com/apache/hop/issues/6060)** [Bug]: Fix show filenames button throws an error in Get Data From XML
- **[Issue 5164](https://github.com/apache/hop/issues/5164)** [Bug]: value type in "Formula" transform injection
- **[Issue 5947](https://github.com/apache/hop/issues/5947)** [Bug]: Parquet Input doesn't read Decimal fields correctly
- **[Issue 6191](https://github.com/apache/hop/issues/6191)** [Task]: Remove PreviewRowsDialogTest
- **[Issue 6171](https://github.com/apache/hop/issues/6171)** [Bug]: Password field not encrypted in rest client transform
- **[Issue 6118](https://github.com/apache/hop/issues/6118)** [Task]: Action Pipeline - add integration tests for execute for every result row
- **[Issue 6107](https://github.com/apache/hop/issues/6107)** [Bug]: ActionPipeline - Execute for every result rows behavior broken
- **[Issue 6109](https://github.com/apache/hop/issues/6109)** [Bug]: Execute for every result row not work
- **[Issue 5369](https://github.com/apache/hop/issues/5369)** [Feature Request]: Unit Test: Enhance Unit Test Dialog
- **[Issue 5978](https://github.com/apache/hop/issues/5978)** [Bug]: "Check server identity" in "Mail" action should be greyed out when "Use secure authentication" is unchecked
- **[Issue 5983](https://github.com/apache/hop/issues/5983)** [Task]: update sqlserver jdbc

## Patch Release 2.16.1

- **[Issue 6008](https://github.com/apache/hop/issues/6008)**: [Bug]: Problem with duplicate field names in timeline after 'Split fields' step
