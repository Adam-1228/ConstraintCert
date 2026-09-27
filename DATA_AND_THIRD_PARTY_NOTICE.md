# Data and third-party notices

Prepared 27 September 2026 for the ConstraintCert reproduction artifact.
Copyright 2026 CHI YONG SEONG for original ConstraintCert material.

## Original material

Original ConstraintCert software, tests, experiment/analysis drivers and original
reproduction documentation are licensed under Apache-2.0 as scoped by the
project's `LICENSE_SCOPE.md` and `LICENSE`. The author authorized the recommended
public-artifact licensing direction on 27 September 2026.

Original synthetic allocations, original measurements and result tables are
made available under Creative Commons Attribution 4.0 International
([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)). Credit CHI YONG SEONG,
*ConstraintCert: Auditing Metadata-Filter Translation and Execution Across Five
Backends*, and identify any modifications. The license does not assert rights
over third-party portions. The manuscript, bibliography and rendered paper are
outside this data/software grant; publication rights remain separate.

## CELLAR metadata

Provider: Publications Office of the European Union, CELLAR. The frozen
10 September 2026 snapshot selects 600 legal-policy metadata anchors using the
included SPARQL query. Fields are `work`, `celex`, `date` and `legal_type`.
No CELLAR legal-document body is included. The projection and synthetic overlays
are research transformations, not official legal interpretations.

CELLAR data and metadata are dedicated under CC0 1.0 according to the
[official legal notice](https://op.europa.eu/en/web/cellar/legal-notice), checked
again on 27 September 2026. No CELLAR logo rights are claimed. The original raw
SPARQL response and derived projection retain separate hashes.

## PyPI Advisory Database through OSV

Provider: [PyPA Advisory Database](https://github.com/pypa/advisory-database)
contributors; distributed through [OSV](https://google.github.io/osv.dev/data/).
The source database is CC BY 4.0. Its exact license is included at
`paper/submission/artifact-candidate/third-party/pypa-advisory-database/LICENSE`,
with pinned commit and retrieval evidence in the adjacent `PROVENANCE.json`.

The snapshot selected the first 600 distinct `PYSEC-` identifiers from its
frozen PyPI modified-ID index before fetching the advisory bodies. Record URLs,
retrieval dates, sizes and SHA-256 hashes are retained in `source-manifest.json`.
Original upstream records retain their own credits and references. No
endorsement by PyPA, OSV or the Publications Office is implied.

For experiment inputs, the projection retains `affected`, advisory identity,
publication/modification/schema fields, source-index modification time and
withdrawn state. `affected` contains package, ranges, versions and source-specific
metadata. Synthetic document identifiers, domain overlays and query allocation
were added by ConstraintCert. Advisory narrative, contacts, credits and exploit
examples are not benchmark features. If original advisory bodies are retained
for source reconstruction, they remain separately labeled upstream source
material, not participant data, ConstraintCert credentials or executable tests.

## Milvus configuration

The pinned upstream Milvus v3.0.0 configuration comes from commit
`f46a0328558be155d11266a1a2b90602ccc9b366` under Apache-2.0. Its exact license is
included in `paper/submission/artifact-candidate/third-party/milvus-v3.0.0/`.
Three recorded experiment configurations are modified derivatives: local runtime
settings were changed and custom access-key fields redacted during the original
runs. Their frozen bytes and hashes are preserved; they must not be represented
as unchanged upstream configuration. Public upstream default-password fields
are configuration examples, not published private project credentials.

## Other dependencies and paper template

Backend executables, containers, installed environments, dependency wheels and
the TeX distribution are not vendored. Their recorded versions and identities
are reproduction dependencies. Official PVLDB template files are also not
redistributed in this artifact; use the exact upstream commit/hashes in
`paper/submission/pvldb-v20/TEMPLATE_PROVENANCE.md`.
