# Claude Opus 4.5 Migration

A focused migration guide for updating prompts, code, and API usage from Claude Sonnet 4.0, Sonnet 4.5, or Opus 4.1 to Opus 4.5.

## What it covers

- Locating model identifiers and API references that need updating.
- Reviewing prompts for behavioral differences.
- Making targeted code and configuration changes.
- Checking compatibility and validating the migrated workflow.

## Scope

This skill does not cover migration from Haiku 4.5. Confirm the target model and supported API configuration before changing production systems.

## Usage

Use this skill when upgrading an existing Claude integration to Opus 4.5. Review the migration steps in `SKILL.md`, inspect every affected call site, apply changes deliberately, and run relevant tests before deployment.

Do not assume a model-string replacement alone is sufficient. Validate output quality, latency, cost, and application-specific behavior after migration.
