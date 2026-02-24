# Verify before shipping

AI-generated code can look correct and still be wrong.

Common failure modes:
- Uses a deprecated API
- Skips edge case handling
- Makes incorrect assumptions about your data model
- Passes tests but does the wrong thing

## What to check
1. Run it — does it actually work?
2. Read it — do you understand every line?
3. Test edge cases — empty input, nulls, large values
4. Check dependencies — are they real and up to date?

## The rule of thumb
If you wouldn't ship code you didn't understand from a colleague, don't ship it from AI either.
