# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.2.2] - 2021-06-21

- Fixed error handling in RPC layer by rethrowing exceptions ([pull request](https://github.com/Shopify/remote-ui/pull/103)).

## [1.2.1] - 2021-06-09

- Fixed an issue where `fromIframe` and `fromInsideIframe` were checking `event.target` instead of `event.source` to ensure messages were coming from the other endpoint.

## [1.2.0] - 2021-06-08

- Adds additional adaptors for converting `iframe` elements into `Endpoint` objects [[#97](https://github.com/Shopify/remote-ui/pull/97)]

## [1.0.2] - 2020-06-24

### Fixed

- Added entry point information to `package.json`.

## [1.0.1] - 2020-06-23

### Fixed

- Fixed a build issue that caused errors when using a number of packages in projects that do not have `core-js@3.x` installed.

## [1.0.0] - 2020-06-23

Initial release.
