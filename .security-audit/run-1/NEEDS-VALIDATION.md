# Security audit report — i18n-auto-translator

- Source ref: `a50995a94e1c6ea45a5b953bc10f748d775d055b`
- Profile: `standard`
- Execution: source-only; no target code, build, browser, provider or live deployment was executed
- Run status: `complete`

## Result

- 1 retained needs-validation record(s); no confirmed severity-bearing findings.
- Coverage units: 1 total; 0 covered; 1 candidate; 0 blocked; 0 deferred.
- Phase 3, structured output validators, and Phase 5 record verification completed.

## Needs validation

| Fingerprint | Title | Blocker |
|---|---|---|
| `i18n:path-traversal-locale-output` | Translator writes locale output using unconstrained language and directory inputs | Exact line and caller reachability need bounded local fixture validation. |
