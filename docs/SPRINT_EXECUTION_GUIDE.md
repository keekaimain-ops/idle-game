# Sprint Execution Guide

**Quick reference for getting work done.**

---

## Folder Structure

```
stories/
├── STORY_01_NAME/
│   └── STORY_OVERVIEW.md    # Description + acceptance criteria
├── STORY_02_NAME/
│   └── STORY_OVERVIEW.md
└── ...
```

---

## Workflow Per Story

1. **Read** STORY_OVERVIEW.md - understand what's needed
2. **Implement** - build it
3. **Test** - verify each acceptance criterion
4. **Update status** - mark as DONE
5. **Commit** - save with story reference
6. **Next story** - repeat

---

## Status Updates

In STORY_OVERVIEW.md, update:
- `Status: TODO` → `Status: IN PROGRESS` → `Status: DONE`

---

## Commit Convention

```
feat(STORY_01): brief description

- What was implemented
- Key changes
```

---

## Interruptions & Bugs

If you discover a bug:
1. Create `bugs/BUG_NNN_description/DESCRIPTION.md`
2. Fix it or defer to backlog
3. See [BUG_TRACKING.md](./BUG_TRACKING.md)
