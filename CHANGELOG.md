# Changelog

All notable changes to the dataset and its repo will be documented in this file.

## Types of changes

- `Added` for new files or rows of data.
- `Changes` for changes in existing files or rows of data.
- `Removed` for removed files or rows of data.
- `Fixed` for any bug fixes in the repo files.

## Unreleased

Unreleased changes must be added here.

## [v1.04] - 2021-10-25

### Added

- `CHANGELOG.md` to keep track of changes to the dataset.
- `Supplementary information.md` to keep track of additional information about the dataset.
- `.gitignore`.
- `data/centreau_qc.zip` to hold the data in compressed form.

### Fixed

- modified `.zenodo.json` to include the correct relation between the current release and the previous releases.

### Removed

- `PCR conditions.md`. Moved info into `Supplementary information.md`.
- `primers.md`. Moved info into `Supplementary information.md`.
- All uncompressed data in `/data`. Replaced with compressed data.


## [v1.03] - 2021-10-21

This release is identical to [v1.02].

## [v1.02] - 2021-10-21

### Added

- `.zenodo.json` file to maintain dataset metadata with each release.

## [1.01] - 2021-10-21

### Added

- Added a DOI tag to `README.md` to make it easier to cite the dataset.

### Removed

- `centreau_qc.zip` since the unzipped version is already in the repo.

## [v1.0] - 2021-10-21

### Added

- `LICENSE` file.
- `README.md` file.
- `data` folder containing the dataset.
- `centreau_qc.zip` file containing a zipped version of the dataset.
- `PCR Conditions.md` file.
- `primers.md` file.
- `src/Picture1.png` file.
