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
