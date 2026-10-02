# Changelog

All notable changes to **drf-haystack** are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### ⚠️ Breaking Changes

- Require Python 3.11 or newer, dropping Python 3.7 to 3.10 ([#224](https://github.com/django-commons/drf-haystack/pull/224), [#307](https://github.com/django-commons/drf-haystack/pull/307), [#321](https://github.com/django-commons/drf-haystack/pull/321))
- Require Django 5.2 or newer, dropping Django 2.2 to 5.1 ([#227](https://github.com/django-commons/drf-haystack/pull/227), [#245](https://github.com/django-commons/drf-haystack/pull/245), [#309](https://github.com/django-commons/drf-haystack/pull/309))
- Require Django REST Framework 3.16 or newer, dropping 3.12 to 3.15 ([#310](https://github.com/django-commons/drf-haystack/pull/310))
- Require django-haystack 3.3.0 or newer, dropping 2.8 to 3.2 ([#301](https://github.com/django-commons/drf-haystack/pull/301))

### 🚀 Features

- Add support for Django 6.1 ([#342](https://github.com/django-commons/drf-haystack/pull/342), [#343](https://github.com/django-commons/drf-haystack/pull/343))
- Add support for Django REST Framework 3.18 ([#340](https://github.com/django-commons/drf-haystack/pull/340))
- Add support for Python 3.13 and 3.14 ([#324](https://github.com/django-commons/drf-haystack/pull/324))
- Add support for Django 6.0 ([#308](https://github.com/django-commons/drf-haystack/pull/308))
- Add support for Django 5.2 ([#306](https://github.com/django-commons/drf-haystack/pull/306))
- Allow django-haystack versions below 4.0 ([#301](https://github.com/django-commons/drf-haystack/pull/301))

### 🐛 Bug Fixes

- Stop raising the "maintainers wanted" `UserWarning` on every import ([#280](https://github.com/django-commons/drf-haystack/pull/280))
- Import `Point` and `D` from `django.contrib.gis` in `SpatialQueryBuilder` and point the missing-library warning at GDAL ([#291](https://github.com/django-commons/drf-haystack/pull/291))
- Remove the use of `six`, which was imported but never declared as a dependency ([#234](https://github.com/django-commons/drf-haystack/pull/234))

### 📝 Documentation

- Move the changelog from the Sphinx docs to `CHANGELOG.md`
- Update repository links after the transfer to django-commons ([#359](https://github.com/django-commons/drf-haystack/pull/359), [#360](https://github.com/django-commons/drf-haystack/pull/360))
- Add a Code of Conduct ([#358](https://github.com/django-commons/drf-haystack/pull/358))
- Sync documented dependency versions with `pyproject.toml` ([#349](https://github.com/django-commons/drf-haystack/pull/349))
- Add maintenance notes ([#288](https://github.com/django-commons/drf-haystack/pull/288))
- Update Python support information ([#250](https://github.com/django-commons/drf-haystack/pull/250))

### 🧰 Maintenance

- Update the Ubuntu version in CI and Read the Docs from 24.04 to 26.04 ([#372](https://github.com/django-commons/drf-haystack/pull/372))
- Pin Renovate to Elasticsearch 7.x ([#370](https://github.com/django-commons/drf-haystack/pull/370))
- Add check-jsonschema git hooks ([#369](https://github.com/django-commons/drf-haystack/pull/369))
- Add Read the Docs config ([#365](https://github.com/django-commons/drf-haystack/pull/365))
- Drop the stale transfer notice and set the development status to 4 - Beta ([#363](https://github.com/django-commons/drf-haystack/pull/363))
- Organize and improve pyproject-fmt settings ([#357](https://github.com/django-commons/drf-haystack/pull/357))
- Add a release pipeline ([#353](https://github.com/django-commons/drf-haystack/pull/353))
- Merge custom dependency install steps in CI ([#341](https://github.com/django-commons/drf-haystack/pull/341))
- Limit Renovate's Python updates ([#337](https://github.com/django-commons/drf-haystack/pull/337))
- Add Django main to the test matrix ([#334](https://github.com/django-commons/drf-haystack/pull/334))
- Update ruff ([#331](https://github.com/django-commons/drf-haystack/pull/331))
- Remove the redundant requirements file ([#329](https://github.com/django-commons/drf-haystack/pull/329))
- Simplify the Sphinx config ([#328](https://github.com/django-commons/drf-haystack/pull/328))
- Remove the deprecated license classifier ([#325](https://github.com/django-commons/drf-haystack/pull/325))
- Add a Django REST Framework version dimension to the test matrix ([#323](https://github.com/django-commons/drf-haystack/pull/323))
- Bump Sphinx to 9.0.4 ([#322](https://github.com/django-commons/drf-haystack/pull/322))
- Improve GitHub Actions workflows ([#319](https://github.com/django-commons/drf-haystack/pull/319))
- Add the google/yamlfmt git hook ([#312](https://github.com/django-commons/drf-haystack/pull/312))
- Migrate the build backend from setuptools to uv_build ([#300](https://github.com/django-commons/drf-haystack/pull/300))
- Set `SECRET_KEY` and `DEFAULT_AUTO_FIELD` explicitly in the test settings ([#299](https://github.com/django-commons/drf-haystack/pull/299))
- Fix dependency versions in the docs build workflow ([#293](https://github.com/django-commons/drf-haystack/pull/293))
- Improve `pathlib.Path` usage ([#292](https://github.com/django-commons/drf-haystack/pull/292))
- Add a CI test pipeline and Elasticsearch 7 setup with uv ([#291](https://github.com/django-commons/drf-haystack/pull/291))
- Update git hooks ([#287](https://github.com/django-commons/drf-haystack/pull/287))
- Add `pyproject.toml` with the project metadata ([#286](https://github.com/django-commons/drf-haystack/pull/286))
- Remove `Pipfile.lock` ([#285](https://github.com/django-commons/drf-haystack/pull/285))
- Update `Pipfile.lock` ([#266](https://github.com/django-commons/drf-haystack/pull/266))
- Add the pyproject-fmt git hook ([#252](https://github.com/django-commons/drf-haystack/pull/252))
- Move the pyupgrade setup from a git hook to ruff ([#251](https://github.com/django-commons/drf-haystack/pull/251))
- Add a docs build workflow ([#247](https://github.com/django-commons/drf-haystack/pull/247))
- Enable zizmor ([#244](https://github.com/django-commons/drf-haystack/pull/244))
- Enable Renovate ([#236](https://github.com/django-commons/drf-haystack/pull/236))
- Add ruff ([#233](https://github.com/django-commons/drf-haystack/pull/233))
- Add pre-commit-hooks ([#232](https://github.com/django-commons/drf-haystack/pull/232))
- Improve the tox config ([#231](https://github.com/django-commons/drf-haystack/pull/231))
- Remove Travis CI ([#228](https://github.com/django-commons/drf-haystack/pull/228))
- Update `Pipfile.lock` ([#225](https://github.com/django-commons/drf-haystack/pull/225))
- Remove Python 3.6 leftovers ([#223](https://github.com/django-commons/drf-haystack/pull/223))
- Add pyupgrade and apply its fixes ([#219](https://github.com/django-commons/drf-haystack/pull/219))
- Rename the default branch from master to main ([#218](https://github.com/django-commons/drf-haystack/pull/218))
- Update dependencies ([#373](https://github.com/django-commons/drf-haystack/pull/373), [#371](https://github.com/django-commons/drf-haystack/pull/371), [#367](https://github.com/django-commons/drf-haystack/pull/367), [#356](https://github.com/django-commons/drf-haystack/pull/356), [#355](https://github.com/django-commons/drf-haystack/pull/355), [#354](https://github.com/django-commons/drf-haystack/pull/354), [#352](https://github.com/django-commons/drf-haystack/pull/352), [#348](https://github.com/django-commons/drf-haystack/pull/348), [#347](https://github.com/django-commons/drf-haystack/pull/347), [#346](https://github.com/django-commons/drf-haystack/pull/346), [#345](https://github.com/django-commons/drf-haystack/pull/345), [#344](https://github.com/django-commons/drf-haystack/pull/344), [#335](https://github.com/django-commons/drf-haystack/pull/335), [#333](https://github.com/django-commons/drf-haystack/pull/333), [#326](https://github.com/django-commons/drf-haystack/pull/326), [#318](https://github.com/django-commons/drf-haystack/pull/318), [#317](https://github.com/django-commons/drf-haystack/pull/317), [#316](https://github.com/django-commons/drf-haystack/pull/316), [#315](https://github.com/django-commons/drf-haystack/pull/315), [#314](https://github.com/django-commons/drf-haystack/pull/314), [#313](https://github.com/django-commons/drf-haystack/pull/313), [#305](https://github.com/django-commons/drf-haystack/pull/305), [#304](https://github.com/django-commons/drf-haystack/pull/304), [#303](https://github.com/django-commons/drf-haystack/pull/303), [#302](https://github.com/django-commons/drf-haystack/pull/302), [#295](https://github.com/django-commons/drf-haystack/pull/295), [#289](https://github.com/django-commons/drf-haystack/pull/289), [#282](https://github.com/django-commons/drf-haystack/pull/282), [#281](https://github.com/django-commons/drf-haystack/pull/281), [#279](https://github.com/django-commons/drf-haystack/pull/279), [#277](https://github.com/django-commons/drf-haystack/pull/277), [#274](https://github.com/django-commons/drf-haystack/pull/274), [#273](https://github.com/django-commons/drf-haystack/pull/273), [#270](https://github.com/django-commons/drf-haystack/pull/270), [#269](https://github.com/django-commons/drf-haystack/pull/269), [#268](https://github.com/django-commons/drf-haystack/pull/268), [#263](https://github.com/django-commons/drf-haystack/pull/263), [#262](https://github.com/django-commons/drf-haystack/pull/262), [#259](https://github.com/django-commons/drf-haystack/pull/259), [#258](https://github.com/django-commons/drf-haystack/pull/258), [#257](https://github.com/django-commons/drf-haystack/pull/257), [#256](https://github.com/django-commons/drf-haystack/pull/256), [#255](https://github.com/django-commons/drf-haystack/pull/255), [#254](https://github.com/django-commons/drf-haystack/pull/254), [#253](https://github.com/django-commons/drf-haystack/pull/253), [#246](https://github.com/django-commons/drf-haystack/pull/246), [#243](https://github.com/django-commons/drf-haystack/pull/243), [#242](https://github.com/django-commons/drf-haystack/pull/242), [#241](https://github.com/django-commons/drf-haystack/pull/241), [#240](https://github.com/django-commons/drf-haystack/pull/240), [#222](https://github.com/django-commons/drf-haystack/pull/222), [#221](https://github.com/django-commons/drf-haystack/pull/221))

## [1.9.3] - 2026-09-16 [YANKED]

Yanked from PyPI with the reason "Too many breaking changes for a patch release". Its changes will be released again as **2.0.0** and are listed under [Unreleased](#unreleased).

## [1.9.1] - 2024-11-05

### 🧰 Maintenance

- Add a deprecation warning about the potential future sunsetting of the project, due to a lack of active maintainers

## [1.9] - 2024-11-04

### 🚀 Features

- Add `id` as an optional serializer field that returns the Haystack internal id ([#193](https://github.com/django-commons/drf-haystack/issues/193))
- Update supported versions of the main dependencies: Django >=2.2,<5.2; Django REST Framework >=3.12.0,<3.16; django-haystack >=2.8,<3.4

### 🐛 Bug Fixes

- Return an empty query object instead of an empty list when no filter is passed ([#202](https://github.com/django-commons/drf-haystack/issues/202))

## [1.8.13] - 2023-10-04

### 🚀 Features

- Support patch versions of Django 4.2.x

### 🧰 Maintenance

- Upgrade a few dependencies

## [1.8.12] - 2023-09-07

### 🚀 Features

- Update supported django-haystack versions

## [1.8.11] - 2021-12-17

### 🚀 Features

- Update supported django-haystack versions

## [1.8.10] - 2021-05-04

### 🚀 Features

- Update supported Django versions
- Update supported Python versions

## [1.8.9] - 2020-10-06

### 🚀 Features

- Update supported Django versions

## [1.8.8] - 2020-10-01

### 🚀 Features

- Update supported Django REST Framework versions

## [1.8.7] - 2020-07-31

### 🚀 Features

- Update supported Python, django-haystack and Django REST Framework versions

## [1.8.6] - 2019-10-13

### ⚠️ Breaking Changes

- Overriding declared fields must now use `serializers.SerializerMethodField()`, which stock Django REST Framework handles ([#139](https://github.com/django-commons/drf-haystack/issues/139))
- Drop Python 2.x support

### 🚀 Features

- Add support for Django REST Framework 3.10.x

## [1.8.5] - 2019-05-21

### 🚀 Features

- Add support for Django 2.2
- Add support for Django REST Framework 3.9.x

## [1.8.4] - 2018-08-14

### 🐛 Bug Fixes

- Fix Django 2.1 support

### 🧰 Maintenance

- Replace `requirements.txt` with `Pipfile` for development dependency management

## [1.8.3] - 2018-06-16

### 🐛 Bug Fixes

- Fix `__in=[...]` and `__range=[...]` filters ([#128](https://github.com/django-commons/drf-haystack/issues/128))

## [1.8.2] - 2018-05-22

### 🐛 Bug Fixes

- Fix `_get_count` for Django REST Framework 3.8

## [1.8.1] - 2018-03-20

### 🐛 Bug Fixes

- Fix errors in the test suite that caused all tests to run on Elasticsearch 1.x

## [1.8.0] - 2018-03-16 [YANKED]

Pulled from PyPI because of critical errors in the test suite.

### ⚠️ Breaking Changes

- Drop support for Django 1.10.x
- Require Django REST Framework 3.7 or newer
- Require django-haystack 2.8 or newer

### 🚀 Features

- Add support for Django 2.0.x

## [1.7.1rc2] - 2018-01-29

### 📝 Documentation

- Fix issues with building the documentation
- Fix minor typos in the documentation

### 🧰 Maintenance

- Drop `unittest2` in favor of the standard library `unittest`

## [1.7.1rc1] - 2018-01-06

Not available on PyPI.

### 🧰 Maintenance

- Lock Django versions to comply with django-haystack requirements
- Require the development release of django-haystack (2.7.1dev0)

## [1.7.0] - 2018-01-06 [YANKED]

Removed from PyPI because of critical bugs.

### ⚠️ Breaking Changes

- Require Django 1.10 or newer
- Require Django REST Framework 3.6.0 or newer

### 🚀 Features

- Add support for the Elasticsearch 2.x Haystack backend

## [1.6.1] - 2017-01-13

### 🐛 Bug Fixes

- Fix the queryset being evaluated when the attribute is set but has no results, which triggered the wrong clause in a condition check ([#88](https://github.com/django-commons/drf-haystack/pull/88), closes [#86](https://github.com/django-commons/drf-haystack/issues/86))

### 📝 Documentation

- Use the correct package name for `libgeos-c1`

### 🧰 Maintenance

- Use the correct package name for `libgeos-c1` in `.travis.yml`

## [1.6.0] - 2016-11-07

### 🚀 Features

- Add Django 1.10 compatibility

### 🐛 Bug Fixes

- Fix multiple minor issues

## [1.6.0rc3] - 2016-06-28

### 🐛 Bug Fixes

- Fix a breaking change introduced by custom serializers for faceted objects ([#61](https://github.com/django-commons/drf-haystack/issues/61))

## [1.6.0rc2] - 2016-06-28

### 🚀 Features

- Add support for using a custom serializer when serializing faceted objects

### 📝 Documentation

- Restructure and update the documentation

## [1.6.0rc1] - 2016-06-23

This release includes breaking changes to the API.

### ⚠️ Breaking Changes

- Drop support for Python 2.6 and Django 1.5, 1.6 and 1.7
- Follow [Haystack's supported versions](https://github.com/django-haystack/django-haystack#requirements)
- Remove the deprecated `SQHighlighterMixin`
- Remove the redundant `BaseHaystackGEOSpatialFilter`. To change the name of `indexes.LocationField`, subclass `HaystackGEOSpatialFilter` directly
- Rework filters:
  - Use more consistent method names
  - All filters follow the same logic for building and applying filters and exclusions
  - All filter classes use a `QueryBuilder` class to validate and build the queries passed to the `SearchQuerySet`
  - Most filters no longer inherit from `HaystackFilter` (except `HaystackAutocompleteFilter` and `HaystackHighlightFilter`) and no longer do basic field filtering. Place filters in the `filter_backends` class attribute in the order they should apply, so inherited filters no longer respond to query parameters they should ignore
- `HaystackFacetSerializer.narrow_url` now returns an absolute URL
- The optional `model` query parameter of `HaystackGenericAPIView.get_object()` now requires `app_label.model` instead of just `model`
- Extract the `more-like-this` detail route and the `facets` list route from the generic `HaystackViewSet`:
  - `more-like-this` is available through `drf_haystack.mixins.MoreLikeThisMixin`
  - `facets` is available through `drf_haystack.mixins.FacetMixin`

### 🚀 Features

- Support all three [built-in pagination classes](https://www.django-rest-framework.org/api-guide/pagination/#api-reference) in `HaystackFacetSerializer`, with a hook for custom pagination classes
- Extract internal fields and the serializer from `HaystackFacetSerializer` to ease customization

### 🐛 Bug Fixes

- Serialize `MultiValueField` and `FacetMultiValueField` items as a JSON array in `HaystackFacetSerializer`

## [1.5.6] - 2015-12-02

### 🐛 Bug Fixes

- Fix `ignore_fields` on `HaystackSerializer` not working unless `exclude` evaluated to `True`

### 🧰 Maintenance

- Remove `elasticsearch` from `install_requires`, since it is only needed with the Elasticsearch backend

## [1.5.5] - 2015-10-31

### 🚀 Features

- Add support for Django REST Framework 3.3.0 (Python 2.7 and Django 1.7 or newer only)

### 🧰 Maintenance

- Lock `elasticsearch` below 2.0.0 ([#29](https://github.com/django-commons/drf-haystack/issues/29))

## [1.5.4] - 2015-10-08

### 🚀 Features

- Add support for serializing faceted results ([#27](https://github.com/django-commons/drf-haystack/issues/27))

## [1.5.3] - 2015-10-05

### 🚀 Features

- Add support for [faceting](https://drf-haystack.readthedocs.io/en/latest/07_faceting.html) ([#11](https://github.com/django-commons/drf-haystack/issues/11))

## [1.5.2] - 2015-08-23

### 🚀 Features

- Add proper support for [multiple search indexes](https://drf-haystack.readthedocs.io/en/latest/09_multiple_indexes.html) ([#22](https://github.com/django-commons/drf-haystack/issues/22))
- Add experimental support for [term boost](https://drf-haystack.readthedocs.io/en/latest/06_term_boost.html), which has upstream issues and does not work as expected
- Add support for negation in filters

## [1.5.1] - 2015-07-28

### 🚀 Features

- Add support for More Like This results ([#10](https://github.com/django-commons/drf-haystack/issues/10))

### 🐛 Bug Fixes

- Return 404 from `HaystackGenericAPIView` detail views when more than one entry is found ([#19](https://github.com/django-commons/drf-haystack/issues/19))

### 🧰 Maintenance

- Deprecate `SQHighlighterMixin` in favor of `HaystackHighlightFilter`

## [1.5.0] - 2015-06-29

### 🚀 Features

- Add support for [field lookups](https://django-haystack.readthedocs.io/en/latest/searchqueryset_api.html#field-lookups) in queries, such as `field__contains=foobar`

### 🐛 Bug Fixes

- Add default `permission_classes` on `HaystackGenericAPIView` to avoid a crash with global Django REST Framework permission classes (see [Permissions](https://drf-haystack.readthedocs.io/en/latest/08_permissions.html))

## [1.4] - 2015-06-14

### 🚀 Features

- Accept a list or tuple of `ignore_fields` on serializer classes to bypass serialization
- Add support for highlighting

### 🐛 Bug Fixes

- Fix geospatial filtering on django-haystack 2.4.x with Elasticsearch

## [1.3] - 2015-05-19

### ⚠️ Breaking Changes

- Remove the hard dependencies on `geopy` and `libgeos`; install them manually to use `HaystackGEOSpatialFilter` ([#5](https://github.com/django-commons/drf-haystack/issues/5))

### 🐛 Bug Fixes

- Return `Http404` from `HaystackGenericAPIView.get_object()` instead of an empty `SearchQuerySet` when no object is found, matching `GenericAPIView.get_object()`

## [1.2] - 2015-03-23

### 🐛 Bug Fixes

- Fix a `MissingDependency` error when using a search backend other than Elasticsearch
- Convert distance to a `D` object before filtering in `HaystackGEOSpatialFilter`

### 🧰 Maintenance

- Add the Python 3 classifier

## [1.1] - 2015-02-16

### 📝 Documentation

- Add documentation

### 🧰 Maintenance

- Add a test suite with almost full coverage
- Set the development status classifier to Beta

## [1.0] - 2015-02-14

### 🎉 Initial Release

- Initial release

[1.0]: https://github.com/django-commons/drf-haystack/releases/tag/v1.0
[1.1]: https://github.com/django-commons/drf-haystack/compare/v1.0...v1.1
[1.2]: https://github.com/django-commons/drf-haystack/compare/v1.1...v1.2
[1.3]: https://github.com/django-commons/drf-haystack/compare/v1.2...v1.3
[1.4]: https://github.com/django-commons/drf-haystack/compare/v1.3...v1.4
[1.5.0]: https://github.com/django-commons/drf-haystack/compare/v1.4...v1.5.0
[1.5.1]: https://github.com/django-commons/drf-haystack/compare/v1.5.0...v1.5.1
[1.5.2]: https://github.com/django-commons/drf-haystack/compare/v1.5.1...v1.5.2
[1.5.3]: https://github.com/django-commons/drf-haystack/compare/v1.5.2...v1.5.3
[1.5.4]: https://github.com/django-commons/drf-haystack/compare/v1.5.3...v1.5.4
[1.5.5]: https://github.com/django-commons/drf-haystack/compare/v1.5.4...v1.5.5
[1.5.6]: https://github.com/django-commons/drf-haystack/compare/v1.5.5...v1.5.6
[1.6.0rc1]: https://github.com/django-commons/drf-haystack/compare/v1.5.6...v1.6.0rc1
[1.6.0rc2]: https://github.com/django-commons/drf-haystack/compare/v1.6.0rc1...v1.6.0rc2
[1.6.0rc3]: https://github.com/django-commons/drf-haystack/compare/v1.6.0rc2...v1.6.0rc3
[1.6.0]: https://github.com/django-commons/drf-haystack/compare/v1.6.0rc3...v1.6.0
[1.6.1]: https://github.com/django-commons/drf-haystack/compare/v1.6.0...v1.6.1
[1.7.0]: https://github.com/django-commons/drf-haystack/compare/v1.6.1...v1.7.0
[1.7.1rc1]: https://github.com/django-commons/drf-haystack/compare/v1.7.0...d5ab341d153bb5633cb0c311ce57c54b81f71696
[1.7.1rc2]: https://github.com/django-commons/drf-haystack/compare/d5ab341d153bb5633cb0c311ce57c54b81f71696...v1.7.1rc2
[1.8.0]: https://github.com/django-commons/drf-haystack/compare/v1.7.1rc2...v1.8.0
[1.8.1]: https://github.com/django-commons/drf-haystack/compare/v1.8.0...v1.8.1
[1.8.2]: https://github.com/django-commons/drf-haystack/compare/v1.8.1...v1.8.2
[1.8.3]: https://pypi.org/project/drf-haystack/1.8.3/
[1.8.4]: https://github.com/django-commons/drf-haystack/compare/v1.8.2...v1.8.4
[1.8.5]: https://github.com/django-commons/drf-haystack/compare/v1.8.4...1.8.5
[1.8.6]: https://github.com/django-commons/drf-haystack/compare/1.8.5...v1.8.6
[1.8.7]: https://pypi.org/project/drf-haystack/1.8.7/
[1.8.8]: https://pypi.org/project/drf-haystack/1.8.8/
[1.8.9]: https://github.com/django-commons/drf-haystack/compare/v1.8.6...v1.8.9
[1.8.10]: https://github.com/django-commons/drf-haystack/compare/v1.8.9...v1.8.10
[1.8.11]: https://pypi.org/project/drf-haystack/1.8.11/
[1.8.12]: https://github.com/django-commons/drf-haystack/compare/v1.8.10...v1.8.12
[1.8.13]: https://github.com/django-commons/drf-haystack/compare/v1.8.12...v1.8.13
[1.9]: https://github.com/django-commons/drf-haystack/compare/v1.8.13...v1.9
[1.9.1]: https://github.com/django-commons/drf-haystack/compare/v1.9...v1.9.1
[1.9.3]: https://github.com/django-commons/drf-haystack/compare/v1.9.1...v1.9.3
[unreleased]: https://github.com/django-commons/drf-haystack/compare/v1.9.1...HEAD
