# Validation status

A fresh isolated Python 3.12 environment was created and all dependencies installed from the package registry. The complete primary analysis was regenerated from raw SensSmartTech recordings in one full-mode invocation, including revised models, 5/8/12-Hz filter sensitivities, signed-delay analyses, native CSV comparisons and supplementary assets. No precomputed result tables were supplied to the runner. The environment dependency check passed.

The final supplementary asset stage was corrected to include three tables and the Holm-adjusted coefficient column formerly added only by the document builder. The entire asset stage was rerun in the same clean environment; upstream numerical processing was unchanged. Regenerated summary tables, historical intermediates and all 17 supplementary numerical tables were independently compared with the reviewed revision outputs using relative and absolute tolerances of 1e-10. See PACKAGE_VERIFICATION.json for every comparison and completed stage. Scientific stage checks passed, including all 2,704 exact 8-Hz foot comparisons and 32 outer method selections.

The historical pilot was separately reproduced in the same clean environment from all 18 raw records. All 11,722 by 12 beat-table entries, 18 by 10 record-table entries and all pilot criteria matched the archived results exactly. The retained tangent primitive is used with a reconstructed fixed-window wrapper: this is computational reproduction, not recovery of the complete original source file or physiological validation. Historical QTDB results were not rerun.

Raw recordings and full per-beat tables are excluded from this archive by an explicit allowlist. The reserved DOI becomes resolvable on publication of the Zenodo record.
