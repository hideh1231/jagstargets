# jagstargets 1.2.3

* Add R-multiverse topic.

# jagstargets 1.2.2

* Use `qs2`.

# jagstargets 1.2.1

* Return `pV` instead of `pD` in DIC info (#35, @giabaio).

# jagstargets 1.2.0

## Invalidating changes

* To align with https://github.com/ropensci/targets/issues/1244 and https://github.com/ropensci/targets/pull/1262, switch the hashing functions from `digest::digest()` to `secretbase::siphash13()`.

## Other changes

* Add the new `description` arguments of `tar_target()` (`targets >= 1.5.1.9001).
* Append model file information to the target descriptions using `tar_map()` (`tarchetypes` >= 0.7.12.9001).

# jagstargets 1.1.0

* Add a `transform` argument to `tar_jags_rep()` to support simulation-based calibration.

# jagstargets 1.0.4

* Migrate docs away from deprecated `targets::tar_path()`.
* Implement resilient reps-specific seeds in the `tar_jags_rep*()` functions.

# jagstargets 1.0.3

* Append a new `.dataset_id` column to target outputs to aid in model comparisons across the same datasets.

# jagstargets 1.0.2

* Support the `repository` argument for `targets` >= 0.11.0.

# jagstargets 1.0.1

* Adjust logo size for README.

# jagstargets 1.0.1

* Reference JOSS paper.

# jagstargets 1.0.0

* Add Zenodo and badge.
* Fix bibliography capitalization.

# jagstargets 0.0.1

* Complete rOpenSci review.
* Allow installation/checks to pass without `rjags` or `R2jags` installed (#18, @jeroen).

# jagstargets 0.0.0.9002

* Replace the `log` argument with `stdout` and `stderr`.
* Switch meaning of `%||%` and `%|||%` to conform to historical precedent.

# jagstargets 0.0.0.9001

* Use `.join_data` list element instead of arguments `copy_data` and `omit_data`.

# jagstargets 0.0.0.9000

* Added a `NEWS.md` file to track changes to the package.
