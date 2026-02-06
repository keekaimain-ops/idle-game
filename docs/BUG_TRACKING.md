# Bug Tracking Process

---

## Structure

```
bugs/
├── BUG_001_description/
│   ├── DESCRIPTION.md    # What's broken
│   ├── FIXED.md          # How it was fixed (when done)
│   └── FAILURES.txt      # Failed attempts (don't repeat these)
└── ...
```

---

## When to Create a Bug

- Test failure
- Unexpected behavior
- User-reported issue
- Regression

---

## Bug Lifecycle

```
1. Bug Found → Create DESCRIPTION.md
2. Attempt Fix
3a. Success → Create FIXED.md
3b. Failure → Log in FAILURES.txt → Retry different approach
4. Bug Resolved
```

---

## DESCRIPTION.md Template

```markdown
# Bug NNN: Short Title

**Reported**: YYYY-MM-DD  
**Status**: Open | In Progress | Fixed  
**Severity**: Critical | High | Medium | Low

## Description
What's happening?

## Expected Behavior
What should happen?

## Reproduction Steps
1. Do this
2. Then this
3. See bug

## Related Story
Story X (if applicable)
```

---

## Rules

1. **Never retry a failed approach** - check FAILURES.txt first
2. **Document immediately** - create ticket when found
3. **Log all failures** - helps future debugging
4. **Verify before marking fixed**
