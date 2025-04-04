# Changelog

All notable changes to this project will be documented in this file.

## 1.1.3

- Fixed more issues in CHANGELOG when displayed on pub.dev

## 1.1.2

- Updated README and added new logo and badges
- Fixed issues in CHANGELOG

## 1.1.1

- Updated README

## 1.1.0

### Added

- Optional singleton pattern (`JozzEvents`) for non-Clean Architecture projects that still provides advantages over alternative solutions
- Comprehensive test suite for the new singleton implementation ensuring reliability
- Complete Clean Architecture integration tutorial in the README with practical examples

### Improved

- README structure and content with clearer, more concise explanations
- Documentation for singleton usage with best practice recommendations
- Overall package organization and developer experience

## 1.0.1

- `JozzBus` interface and `JozzBusService` implementation
- Strongly-typed domain event system
- Fluent API (`emitEvent`)
- Lifecycle support with `JozzLifecycleMixin`
- Subscription helpers (`JozzBusSubscription`)
- Auto disposal of event listeners
