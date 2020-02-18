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
