# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html),
and is generated by [Changie](https://github.com/miniscruff/changie).

## v0.5.2 - 2024-01-08

### Fixed

* Fix referenced service name

## v0.5.1 - 2024-01-08

### Changed

* Allow configuration of HAProxy image
* Add `hairpin-proxy` to generated resource names

### Fixed

* Fix HAProxy image reference

## v0.5.0 - 2024-01-08

### Changed

* Configuration of CoreDNS port
* Let controller manage HAProxy deployments ([webofmars fork](https://github.com/webofmars/hairpin-proxy))

## v0.4.0 - 2022-12-07

### Changed

* Split up label indicating targeted ingress service

### Fixed

* Retry creating deployments/services if updating fails
* Proper handling of updating resources vs. creating of services and deployments
