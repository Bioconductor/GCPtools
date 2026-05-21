## Changes in version 1.4.0

* Update examples and documentation to use a truly public Landsat dataset
  (`gs://gcp-public-data-landsat/...`) instead of the restricted genomics
  dataset.
* Update `gsutil_pipe()` examples to read structured text data with
  `readLines()` rather than `read.csv()`.
* Fix argument passing and shell quoting in `gsutil_rsync()` for the `exclude`
  pattern.
* Fix shell quoting in `gsutil_pipe()`.

## Changes in version 1.0.0

* Initial Bioconductor release!
