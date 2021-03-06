**See [the release process docs](docs/howtos/cut-a-new-release.md) for the steps to take when cutting a new release.**

# Unreleased Changes

## General

- Remove the node.js integration tests helper and removes node from the circleci environment. ([#3187](https://github.com/mozilla/application-services/pull/3187))
- Put `backtrace` behind a cargo feature. ([#3213](https://github.com/mozilla/application-services/pull/3213))
- Move sqlite dependency down from rc_cryto to nss_sys. ([#3198](https://github.com/mozilla/application-services/pull/3198))
- Adds jwe encryption in scoped_keys. ([#3195](https://github.com/mozilla/application-services/pull/3195))
- Adds an implementation for [pbkdf2](https://www.ietf.org/rfc/rfc2898.txt). ([#3193](https://github.com/mozilla/application-services/pull/3193))


[Full Changelog](https://github.com/mozilla/application-services/compare/v60.0.0...master)
