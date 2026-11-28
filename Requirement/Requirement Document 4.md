# Requirement Document 4

> Summary: This document adds login page requirements — email and password sign-in, rate-limited failed login attempts per the architecture specification, and a sub-2-second login response time.

## Functional Requirements

1. **FR-7:** The login page shall support email and password sign-in.
2. **FR-8:** Failed login attempts shall be rate-limited per the architecture specification ([[Architecture Spec]]).

## Non-Functional Requirements

- **NFR-3:** Login response time under 2 seconds.

## Related notes

- [[Architecture Spec]] — referenced by FR-8 as the basis for rate-limiting failed login attempts.
- [[Requirement Document 3]] — FR-6 authentication also follows the Architecture Spec.
