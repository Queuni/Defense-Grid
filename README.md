# Defense Grid

A tower defense game prototype built in Unity using the Hybrid ECS (Entity Component System) architecture.

## Requirements

- **Unity:** 2018.1 or newer (project created with 2018.3.0f2)

## Getting Started

1. Clone or download this repository.
2. Open the project in Unity Hub (Add → select the project folder).
3. Open the **Boot** scene from `Assets/Scenes/` and press Play.

## Project Structure

- **Assets/Scenes/** — Boot, MainMenu, and level scenes
- **Assets/Scripts/** — Core logic and ECS-related code
- **Assets/Configs/** — Enemy, gun, and wave configuration assets
- **Assets/Prefabs/** — UI, environment, enemies, and props
- **Assets/Textures/** — UI, props, environment, and enemy art

## License

See the [LICENSE](LICENSE) file in this repository.

- Add integration test that covers the full flow from request to response

- Refactor the parser to use a proper state machine instead of regex

- Remove hardcoded credentials and move to env-based configuration

- Update the deployment docs with the new environment variables

- Remove the experimental feature that didn't make it into the release

- Correct the timestamp format to use ISO 8601 for consistency

- Support passing secrets via a separate file for security

- Improve the default config so it works out of the box for dev

- Implement a simple metrics endpoint for Prometheus scraping

- Simplify the dependency injection so it's easier to mock in tests

- Correct typo in the error message shown when validation fails

- Bump the CI image to use the latest stable runner version

- Support optional config file path via env var for easier deployment

- Simplify the validation flow by reusing the same schema

- Adjust the batch size to reduce memory usage on large inputs

- Clean up the test fixtures and move shared data to a single file

- Fix bug where the parser would hang on malformed input

- Fix bug where the parser would hang on malformed input

- Bump minimum Python version to 3.10 and update type hints accordingly

- Support custom headers in the client for API key or auth tokens

- Support loading config from multiple files with later overriding earlier

- Fix the off-by-one error in the date range iterator

- Fix issue where empty input was not validated before passing to the parser

- Support passing options through the config file as well as CLI

- Fix issue where empty input was not validated before passing to the parser

- Support both relative and absolute paths for the config file

- Fix the encoding issue when reading config files with non-ASCII

- Update the API docs with the new query parameters and examples

- Clean up the formatting and run the linter on the changed files

- Simplify the CLI by merging the two similar subcommands into one

- Fix the encoding issue when reading config files with non-ASCII

- Support custom headers in the client for API key or auth tokens

- Improve test coverage for the helpers module to above 90%

- Correct the formula used for calculating the backoff delay

- Simplify the config validation by using a declarative schema

- Simplify the validation flow by reusing the same schema

- Adjust log level for noisy messages that were filling the logs

- Handle missing optional field in the response without raising

- Simplify the dependency injection so it's easier to mock in tests

- Refactor exports so the public API is clearer and easier to use

- Simplify error messages so they are actionable for the end user

- Clean up the TODO comments that were already addressed

- Improve the setup script to check for required tools before running

- Clean up debug print statements before the release

- Improve the startup time by lazy-loading the heavy modules

- Implement fallback to default value when config key is missing

- Support loading config from multiple files with later overriding earlier

- Improve the default config so it works out of the box for dev

- Clean up the commented-out code that was left from debugging

- Remove the feature flag now that the feature is fully rolled out

- Clean up the test fixtures and move shared data to a single file

- Clean up the commented-out code that was left from debugging

- Fix the off-by-one error in the date range iterator

- Refactor the main entry point to make it easier to test

- Handle edge case when the response body is empty but status is 200

- Improve performance by caching the result of the expensive lookup

- Handle the case when the config file exists but is not readable

- Clean up the formatting and run the linter on the changed files

- Clean up duplicate logic between the sync and async code paths

- Refactor exports so the public API is clearer and easier to use

- Bump the dependency to fix the compatibility issue with Python 3.12

- Implement a simple health check endpoint for the load balancer

- Refactor the helper to accept an optional callback for progress

- Adjust timeout and retry settings based on production observations

- Implement proper backoff with jitter for the retry logic

- Update README with installation steps and environment variable documentation

- Adjust log level for noisy messages that were filling the logs

- Handle the duplicate key case by merging the values instead of failing

- Improve the startup time by lazy-loading the heavy modules

- Bump version to 1.2.0 and add changelog entry for the new features

- Implement a simple metrics endpoint for Prometheus scraping

- Handle missing optional field in the response without raising

- Update the contributing guide with the new review process

- Fix the memory leak in the long-running worker process

- Update dependencies and resolve compatibility warning from pytest
