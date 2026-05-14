# Verification Matrix

## Frontend change

Prefer, in order:

1. targeted unit/component tests
2. typecheck
3. lint
4. build
5. affected e2e test if available

## Backend API change

Prefer, in order:

1. targeted unit tests
2. integration tests around the changed endpoint/service
3. typecheck or static analysis
4. lint
5. full test suite if practical

## Refactor

Prefer:

1. tests covering affected behavior before and after
2. typecheck
3. lint
4. full suite when feasible

## Bug fix

Prefer:

1. reproduce the bug if possible
2. add regression test
3. fix
4. run regression test
5. run nearby tests

