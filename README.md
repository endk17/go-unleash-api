# go-unleash-api

This is a Go client library to interact with the [Unleash Admin API](https://docs.getunleash.io/api) - in early development.

**Requires `unleash-server` v4.13 or higher.**

## Supported Endpoints

- [x] Features
  - [x] GetFeature
  - [x] CreateFeature
  - [x] UpdateFeature
  - [x] ArchiveFeature
  - [x] GetAllFeaturesByProject
  - [x] AddStrategyToFeature
  - [x] UpdateFeatureStrategy
  - [x] DeleteStrategyFromFeature
  - [x] EnableFeatureOnEnvironment
- [x] Strategies
  - [x] CreateStrategy
  - [x] UpdateStrategy
  - [x] DeprecateStrategy
  - [x] ReactivateStrategy
  - [x] GetAllStrategies
  - [x] GetStrategyByName
- [x] Projects
  - [x] GetProjectById
  - [x] CreateProject
  - [x] UpdateProject
  - [x] DeleteProject
- [x] Features v2
  - [x] AddUserProject
  - [x] UpdateUserProject
  - [x] DeleteUserProject