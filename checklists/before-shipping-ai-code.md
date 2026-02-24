# Before shipping AI-generated code

A quick checklist to run before merging or deploying code that was written or significantly modified by AI.

## Understanding
- [ ] I can explain what every function does
- [ ] I understand why the logic is structured this way
- [ ] I've read all imports and dependencies

## Correctness
- [ ] The code runs without errors
- [ ] It handles empty or null inputs correctly
- [ ] It handles error cases explicitly
- [ ] Edge cases have been considered

## Security
- [ ] No secrets or credentials are hardcoded
- [ ] User input is validated or sanitized where needed
- [ ] No obvious injection risks

## Dependencies
- [ ] All imported packages are real and exist
- [ ] Package versions are current and not deprecated
- [ ] No unnecessary dependencies were added

## Tests
- [ ] Existing tests still pass
- [ ] New behavior has test coverage
- [ ] Tests cover at least one failure case

---

If any box is unchecked, fix it before shipping.
