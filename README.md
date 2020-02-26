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
