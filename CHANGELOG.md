# epytope: Changelog

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## v3.0.0dev - [date]

Initial release of `epytope`. `epytope` is the successor project of `FRED-2`, which was renamed to a more versioning friendly base name.

### `Added`

- [#6](https://github.com/KohlbacherLab/epytope/pull/6) - Add CI for external tools
- [#24](https://github.com/KohlbacherLab/epytope/pull/24) - Add `keras` dependency
- [#26](https://github.com/KohlbacherLab/epytope/pull/26) - Add a license file
- [#31](https://github.com/KohlbacherLab/epytope/pull/31) - Add deployment to `PyPI`
- [#42](https://github.com/KohlbacherLab/epytope/pull/42) - Add new `Syfpeithi` matrices
- [#46](https://github.com/KohlbacherLab/epytope/pull/46) - Add support for `NetMHCII 2.3` and `NetMHCIIpan 4.0`

### `Changed`

- [#1](https://github.com/KohlbacherLab/epytope/pull/1) - Switch CI/CD from Travis to GitHub Actions
- [#9](https://github.com/KohlbacherLab/epytope/pull/9) - Initial `Python 2` to `Python 3` conversion based on 2to3conv
- [#20](https://github.com/KohlbacherLab/epytope/pull/20) - Use logging module rather than print calls across the library
- [#23](https://github.com/KohlbacherLab/epytope/pull/23) - Rename the package from `FRED-2` to `epytope`
- [#25](https://github.com/KohlbacherLab/epytope/pull/25) - Refactor CI to use more `pip` and less `conda`
- [#42](https://github.com/KohlbacherLab/epytope/pull/42) - Extend `EpitopePredictionResult` structure to store `rank`-based scores

### `Fixed`

- [#11](https://github.com/KohlbacherLab/epytope/pull/11) - Fix `Python` version matrix in CI, remove versions that fail
- [#16](https://github.com/KohlbacherLab/epytope/pull/16) - Fix epitope prediction 2to3 bugs and tests
- [#17](https://github.com/KohlbacherLab/epytope/pull/17) - Fix Invalid subprocess handling and `mhcflurry` polluting stdout
- [#18](https://github.com/KohlbacherLab/epytope/pull/18) - Fix external (`NetMHC` tool family) epitope prediction error and temp file handling
- [#46](https://github.com/KohlbacherLab/epytope/pull/46) - Fix issues with MHC class-II `CombinedAlleles` [#45](https://github.com/KohlbacherLab/epytope/issues/45)
- [#46](https://github.com/KohlbacherLab/epytope/pull/46) - Do not override `Allele` objects [#38](https://github.com/KohlbacherLab/epytope/issues/38)