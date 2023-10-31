# test-data

A repository to store integration/ML test data.

## Rational

In order to launch some integration (or machine-learning specific) tests, we need to process some assets (images, JSON files,...).
However, these files are quite big, and can't possibly be stored in the main repository (robotoff, openfoodfacts-python) to avoid it to be bloated. On Robotoff, we used git lfs, but we very hit Github free-tier API limits.

Consequently, this repository is used to get a permalink to an asset that's not subject to downtime or deletion.
It's then the responsability of the project to download the appropriate files.
