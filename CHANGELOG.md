# Changelog


## 2020-03-08
- Remove the deprecated wrapper and use the library API directly

## 2020-03-26
- Handle timeout gracefully and return a clear error to the caller

## 2020-03-26
- Remove the unused parameter that was left from an old refactor

## 2020-03-26
- Fix bug where the parser would hang on malformed input

## 2020-04-25
- Add integration test that covers the full flow from request to response

## 2020-05-13
- Simplify the build script by using the same steps for dev and prod

## 2020-05-13
- Implement request ID propagation for better tracing across services

## 2020-05-25
- Bump the version and tag the release in the repo

## 2020-06-24
- Implement a small in-memory cache for the config to avoid re-reading

## 2020-07-18
- Bump minimum Python version to 3.10 and update type hints accordingly

## 2020-02-12
- Remove the feature flag now that the feature is fully rolled out

## 2020-02-14
- Bump the version and tag the release in the repo

## 2020-02-14
- Correct the formula used for calculating the backoff delay

## 2020-02-16
- Refactor the main entry point to make it easier to test

## 2020-02-18
- Add a comment explaining why we disable the linter on this line

## 2020-02-18
- Fix the test that was flaky due to reliance on system time

## 2020-02-18
- Fix the test that was flaky due to reliance on system time

## 2020-02-20
- Fix the ordering of middleware so auth runs before the handler

## 2020-02-20
- Simplify the dependency injection so it's easier to mock in tests

## 2020-02-20
- Remove the temporary debug endpoint before the release

## 2020-02-24
- Handle the case when the config file exists but is not readable

## 2020-02-26
- Remove the unused parameter that was left from an old refactor

## 2020-03-05
- Simplify the dependency injection so it's easier to mock in tests

## 2020-03-07
- Simplify the auth flow by using a single token source

## 2020-03-09
- Add proper error handling for invalid config so the app doesn't crash on startup

## 2020-03-09
- Handle the case when the config file exists but is not readable

## 2020-03-09
- Correct the default value for the feature flag in production

## 2020-03-13
- Refactor config loading into a separate module for better testability

## 2020-03-13
- Improve the error recovery when the database connection is lost

## 2020-03-17
- Support environment-specific overrides via separate config files

## 2020-03-19
- Simplify the config merge logic so overrides are predictable

## 2020-03-21
- Adjust the threshold so we only log when it's actually an issue

## 2020-03-21
- Add a smoke test that runs in CI to catch obvious regressions

## 2020-03-27
- Support passing options through the config file as well as CLI

## 2020-03-27
- Refactor exports so the public API is clearer and easier to use

## 2020-03-27
- Adjust timeout and retry settings based on production observations

## 2020-03-31
- Handle the duplicate key case by merging the values instead of failing

## 2020-04-02
- Implement proper cleanup of resources when the process receives SIGTERM

## 2020-04-06
- Improve the startup time by lazy-loading the heavy modules

## 2020-04-08
- Adjust the batch size to reduce memory usage on large inputs

## 2020-04-10
- Correct the default path used when no config file is specified

## 2020-04-12
- Bump the Docker base image to get the latest security patches

## 2020-04-12
- Add a small delay between retries to avoid thundering herd

## 2020-04-14
- Support passing options through the config file as well as CLI

## 2020-04-14
- Fix bug where the parser would hang on malformed input

## 2020-04-16
- Refactor the helper to accept an optional callback for progress

## 2020-04-16
- Add proper error handling for invalid config so the app doesn't crash on startup

## 2020-04-20
- Simplify the config merge logic so overrides are predictable

## 2020-04-20
- Handle missing optional field in the response without raising

## 2020-04-22
- Improve error message when the required env var is not set

## 2020-04-22
- Remove obsolete workaround now that the upstream bug is fixed

## 2020-04-28
- Add proper error handling for invalid config so the app doesn't crash on startup

## 2020-04-28
- Correct the default value for the feature flag in production

## 2020-05-06
- Support both relative and absolute paths for the config file

## 2020-05-08
- Update the changelog with the fixes included in this release

## 2020-05-08
- Support config reload without restart via SIGHUP or file watch

## 2020-05-08
- Support passing options through the config file as well as CLI

## 2020-05-20
- Implement request ID propagation for better tracing across services

## 2020-05-20
- Support passing secrets via a separate file for security

## 2020-05-22
- Bump the dependency to fix the compatibility issue with Python 3.12

## 2020-06-03
- Adjust log level for noisy messages that were filling the logs

## 2020-06-09
- Refactor config loading into a separate module for better testability

## 2020-06-09
- Implement request ID propagation for better tracing across services
