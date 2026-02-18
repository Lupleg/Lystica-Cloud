# Changelog

All notable changes to the `lystica-cloud` SDK will be documented in this file.

## [0.1.0] - 2026-02-18

### Added

- Initial release of the Lystica Cloud SDK
- **Contacts** — list, get, create, update, delete, search, tag management, auto-pagination
- **Companies** — list, get, search, list contacts, auto-pagination
- **Emails** — send, get status, list, cancel scheduled
- **Lists** — create, update, delete, add/remove contacts
- **Webhooks** — signature verification utility
- **API key verification** — `verifyKey()` method
- Cursor-based pagination with `listAll()` async generators
- Automatic retry with exponential backoff and jitter
- Typed errors: `LysticaAuthError`, `LysticaForbiddenError`, `LysticaNotFoundError`, `LysticaValidationError`, `LysticaRateLimitError`, `LysticaNetworkError`
- Dual CJS/ESM output with full TypeScript declarations
- Support for `lys_live_` (production) and `lys_test_` (sandbox) API keys
