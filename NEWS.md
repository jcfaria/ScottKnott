# ScottKnott 1.3-4 (2026-03-03)

## Changes

- Removed the dependency on the `doBy` package. The `doBy::LSmeans` function
  left undesirable residue in the console or when used with Sweave or knitr.
- Added the `emmeans` package as a dependency.
- All internal LSmeans functions have been replaced by `emmeans`.

---

# ScottKnott 1.3-2 (2025-03-14)

## Bug Fixes

- Fixed the `mtext` command line that was out of context of the `axis1` argument.
- Fixed missing package anchors in `xtable.SK.Rd`.
- In all functions that use `LSmeans` as object, replaced `aux_mt$coef[,1]`
  with `with(aux_mt, estimate)`.

---

# ScottKnott 1.3-2 (2023-08-30)

## Changes

- Adjustment of files as required by CRAN.

---

# ScottKnott 1.3-1 (2023-06-21)

## New Features

- Added new arguments `axis1` and `axis2` to the `plot` function, giving
  greater flexibility to users who want to customise their own axes.

## Changes

- Adjustment of files as required by CRAN.

---

# ScottKnott 1.3-0 (2021-06-17)

## Changes

- Fixed the `Version`, `Date` and `Description` items of the `DESCRIPTION` file.

---

# ScottKnott 1.2-9 (2020-10-05)

## Changes

- All documentation was corrected.

---

# ScottKnott 1.2-8 (2020-10-02)

## New Features

- New method for unbalanced data.
- Added methods for `formula`, `lm` and `lmerMod` classes.

## Changes

- All documentation was corrected.

---

# ScottKnott 1.2-7 (2018-06-07)

## Changes

- Corrections in the documentation in accordance with CRAN requirements.

---

# ScottKnott 1.2-6 (2015-09-21)

## Bug Fixes

- Fixed a small bug in `SK.nest.aov.R`: lines that had `[:punct:]` (wrongly)
  were changed to `[[:punct:]]` (correctly).

## Changes

- Corrected documentation in accordance with CRAN requirements.

---

# ScottKnott 1.2-5 (2014-09-29)

## Bug Fixes

- Fixed a small bug in `SK.aov.R`: line 44 had an object `sig.level=0.05`
  that prevented the exchange of probability.

## Changes

- Updated the `CITATION` file. The package is now published in a scientific
  journal.
- Added GitHub and LEC URLs to the `DESCRIPTION` file.

---

# ScottKnott 1.2-4 (2013-04-15)

## Changes

- All calls to the old method `model.frame.aovlist` now call the generic
  to meet CRAN requirements.
- Released to CRAN.

---

# ScottKnott 1.2-3 (2013-04-15)

## Changes

- The source code has been deeply improved.
- The documentation has been deeply updated.

---

# ScottKnott 1.2-2 (2013-03-17)

## New Features

- New options related to the dispersion of the means.

---

# ScottKnott 1.2-1 (2012-12-10)

## Bug Fixes

- Fixed a small bug in `SK.nest.aovlist.R`: lines that had `[:punct:]`
  (wrongly) were changed to `[[:punct:]]` (correctly).

## New Features

- New dataset: `SPET` (Split-plot in time).

---

# ScottKnott 1.2-0 (2012-10-06)

## Changes

- Ivan Bezerra Allaman joined the project as co-author.
- Sergio Oliveira no longer works on the project.
- Changes in `SK.nest.aov.R` make it easier to study interactions.
- The source code was improved.
- Overall improvements in documentation and demos.

---

# ScottKnott 1.1-3 (2012-04-02)

## Changes

- Cosmetic changes to meet CRAN requirements.

---

# ScottKnott 1.1-2 (2011-05-11)

## New Features

- New dataset: `sorghum`.
- The notation of factorial models now agrees with Wilkinson and Rogers (1973).
- The methods `SK.nest.aov` and `SK.nest.aovlist` were enhanced to adapt to
  the new notation.
- The demos were enhanced.

---

# ScottKnott 1.1-1 (2010-06-13)

## Changes

- The S3 method `summary.SK.nest` was enhanced.

---

# ScottKnott 1.1-0 (2010-03-28)

## Changes

- The classes `SK` and `SK.nest` have been simplified.
- The S3 method to plot `SK` and `SK.nest` objects was enhanced.

---

# ScottKnott 1.0-0 (2009-01-23)

## Changes

- Initial release to CRAN.
