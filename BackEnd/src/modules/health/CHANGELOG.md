# health module changelog

All notable changes to the `health` backend module are documented here.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/)
and this module adheres to [Semantic Versioning](https://semver.org/).

## [Unreleased]

### Added
- `database-pool.config.ts` for env-var-driven PostgreSQL connection pool settings (`DB_POOL_MIN`, `DB_POOL_MAX`, `DB_POOL_IDLE_TIMEOUT_MS`, `DB_POOL_CONNECTION_TIMEOUT_MS`) with validation and production-ready defaults.

### Changed
- `ExternalHealthService` now uses `PooledHttpClientService` (keep-alive connection pool, 3 s `short` timeout budget) instead of ad-hoc `axios` calls for Stellar Horizon and SendGrid health checks. `HttpClientModule` added to `HealthModule` imports.
