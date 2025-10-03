# OPA Java SDK Changelog

## 2.2.0

This release includes release engineering improvements, and no significant code or dependency changes.

## 2.1.1

This release is the first release of the OPA Java SDK after its donation to the `open-policy-agent` Github Organization.
No significant code changes are included in this release, as most changes were localized to the release workflows.

## 1.6.0

* Fixed omission of jackson-databind dependency type change to `api`, which was supposed to go out with 1.5.3.

## 1.5.3

* Marked jackson-databind as an `api` dependency in addition to jackson-core.
* Fixed a bug where `OPALatencyMeasuringHTTPClient` would report results in ns rather than ms.

## 1.5.2

* Fixed a bug where instantiating `OPALatencyMeasuringHTTPClient` with the default constructor could result in a null pointer exception while formatting messages.

## 1.5.1

* Regenerated low-level API with Speakeasy 1.351.2
* Release `OPALatencyMeasuringHTTPClient`

