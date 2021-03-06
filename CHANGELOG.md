# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Changed 
- Switched SNS to argus. [#168](https://github.com/xmidt-org/tr1d1um/pull/168)
- Update references to the main branch. [#144](https://github.com/xmidt-org/talaria/pull/144) 

## [v0.5.1]
### Fixed
- Specify allowed methods for webhook endpoints. [#163](https://github.com/xmidt-org/tr1d1um/pull/163)
- Revert to default http mux routeNotFound handler for consistency. [#163](https://github.com/xmidt-org/tr1d1um/pull/163)
- Json content type header should only be specified in 200 OK responses for stat endpoint. [#166](https://github.com/xmidt-org/tr1d1um/pull/166)
- Add special field in spruce config yml. [#159](https://github.com/xmidt-org/tr1d1um/pull/159)

### Added
- Add docker entrypoint. [154](https://github.com/xmidt-org/tr1d1um/pull/154)

### Changed
- Register for specific OS signals. [#162](https://github.com/xmidt-org/tr1d1um/pull/162)

## [v0.5.0]
- Add optional config for tr1d1um to use its own authentication tokens (basic and jwt supported). [#148](https://github.com/xmidt-org/tr1d1um/pull/148)
- Remove mention of XPC team in error message. [#150](https://github.com/xmidt-org/tr1d1um/pull/150)
- Bump golang version. [#152](https://github.com/xmidt-org/tr1d1um/pull/152)
- Use scratch as docker base image instead of alpine. [#152](https://github.com/xmidt-org/tr1d1um/pull/152)
- Add docker automation. [#152](https://github.com/xmidt-org/tr1d1um/pull/152)

## [v0.4.0]
- Fix a bug in which tr1d1um was returning 500 for user error requests. [#146](https://github.com/xmidt-org/tr1d1um/pull/146)
- Added endpoint regex configuration for capabilityCheck metric. [#147](https://github.com/xmidt-org/tr1d1um/pull/147)

## [v0.3.0]
 - Add feature to disable verbose transaction logger. [#145](https://github.com/xmidt-org/tr1d1um/pull/145)
 - Changed WRP message source. [#144](https://github.com/xmidt-org/tr1d1um/pull/144)

## [v0.2.1]
 - Moving partnerIDs to tr1d1um.
 - Added fix to correctly parse URL for capability checking. [#142](https://github.com/xmidt-org/tr1d1um/pull/142)

## [v0.2.0]
 - Bumped bascule, webpa-common, and wrp-go.
 - Removed temporary `/iot` endpoint.
 - Updated release pipeline to use travis. [#135](https://github.com/xmidt-org/tr1d1um/pull/135)
 - Added configurable way to check capabilities and put results into metrics, without rejecting requests. [#137](https://github.com/xmidt-org/tr1d1um/pull/137)

## [v0.1.5]
 - Migrated from glide to go modules.
 - Bumped bascule version and removed any dependencies on webpa-common secure package. 

## [v0.1.4]
- Add logging of WDMP parameters.

## [v0.1.2]
- Switching to new build process.

## [0.1.1] - 2018-04-06
### Added
- Initial creation.

[Unreleased]: https://github.com/xmidt-org/tr1d1um/compare/v0.5.1...HEAD
[v0.5.1]: https://github.com/xmidt-org/tr1d1um/compare/v0.5.0...v0.5.1
[v0.5.0]: https://github.com/xmidt-org/tr1d1um/compare/v0.4.0...v0.5.0
[v0.4.0]: https://github.com/xmidt-org/tr1d1um/compare/v0.3.0...v0.4.0
[v0.3.0]: https://github.com/xmidt-org/tr1d1um/compare/v0.2.1...v0.3.0
[v0.2.1]: https://github.com/xmidt-org/tr1d1um/compare/v0.2.0...v0.2.1
[v0.2.0]: https://github.com/xmidt-org/tr1d1um/compare/v0.1.5...v0.2.0
[v0.1.5]: https://github.com/xmidt-org/tr1d1um/compare/v0.1.4...v0.1.5
[v0.1.4]: https://github.com/xmidt-org/tr1d1um/compare/v0.1.2...v0.1.4
[v0.1.2]: https://github.com/xmidt-org/tr1d1um/compare/0.1.1...v0.1.2
[0.1.1]: https://github.com/xmidt-org/tr1d1um/compare/e34399980ec8f7716633c8b8bc5d72727c79b184...0.1.1
