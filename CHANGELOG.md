# Changelog

## [1.1.0]
### Added
- SecurityContext option to each container's template.

### Changed
- Updated password for PostgreSQL.
- Standardized Infinispan configuration.
- Enhanced Keycloak environment variables for compatibility with version 26.0.8.

### Fixed
- Corrected `check-database` init container image value reference.

### Removed
- Deprecated import of H2M realms (functionality was incomplete and not relevant).
- Removed AWS-specific `storageClassName` from general templates.

## [1.0.0] - Init

