# Project Context — AI-to-AI Handoff

> **Last updated:** `<YYYY-MM-DD HH:MM>`
> **Updated by:** `<AI name/model>`
> **Session #:** `<number>`
> **Overall status:** `<not started | in progress | blocked | done>`

---

## 📌 Instructions for the AI (read first)

This file is the **shared memory** between sessions. It exists so another AI can pick up your work without re-reading everything.

**When STARTING a session:**
1. Read this entire file before taking any action.
2. Check **section 9. Next steps** and **section 8. In progress** to know where to resume.
3. Verify that the real project state matches what is described here (files may have changed).

**While working:**
- Update sections 7, 8 and 10 at every milestone, not only at the end.

**When tokens are running low (~10–15% left):**
1. STOP starting new tasks.
2. Fill in / update ALL sections below.
3. Be specific: file paths, function names, exact commands, error messages.
4. Write section 9 as if the reader has no memory of the conversation.

**Filling rules:**
- ✅ Be concise and factual. Prefer lists and tables.
- ✅ Record the **why** behind decisions, not just the what.
- ❌ **NEVER write secrets here:** passwords, tokens, API keys, `JWT_SECRET`, OAuth client IDs, private folder IDs, government IDs, real customer data, personal emails, or paths that reveal a username. Use `<placeholder>` and say **where** the real value lives (e.g. "in `.env.local`").
- ❌ Don't delete useful history; move finished items to section 7.

---

## 1. Project goal

**What it is:**
`<2–3 line description>`

**Target user:**
`<who uses it>`

**Goal of the current session/task:**
`<what is being attempted right now>`

---

## 2. Stack and environment

| Layer | Technology / version |
|-------|----------------------|
| `<e.g. Frontend>` | `<...>` |
| `<...>` | `<...>` |

**OS / shell:** `<...>`
**Environment constraints:** `<e.g. PowerShell blocks .ps1 scripts, use cmd.exe>`

**How to run:**
```
<command 1>
<command 2>
```

**How to verify (tests / typecheck / lint):**
```
<commands>
```

---

## 3. File structure

```
<short tree with a one-line comment per relevant item>
```

**Sensitive files (never commit, never paste their contents here):**
| File | Purpose | Where to get it |
|------|---------|-----------------|
| `<...>` | `<...>` | `<...>` |

---

## 4. Architecture and key decisions

| # | Decision | Reason | Date |
|---|----------|--------|------|
| 1 | `<...>` | `<...>` | `<...>` |

**Code conventions adopted:**
- `<e.g. monetary values stored as integer cents>`

---

## 5. Data model / API

**Main entities:**
| Entity | Relevant fields | Notes |
|--------|-----------------|-------|
| `<...>` | `<...>` | `<...>` |

**Main endpoints / interfaces:**
```
<METHOD /route — description>
```

---

## 6. Implemented business rules

1. `<rule>`
2. `<rule>`

---

## 7. ✅ Done

| Date | What was done | Files touched |
|------|---------------|---------------|
| `<YYYY-MM-DD>` | `<...>` | `<path/file>` |

---

## 8. 🔧 In progress

**Current task:** `<description>`

**Exact state where I stopped:**
`<e.g. function X created in file Y, still needs wiring into route Z>`

**Modified files not yet validated:**
- `<path>` — `<what changed>`

**Last command run and its result:**
```
<command>
<relevant output/error>
```

---

## 9. ➡️ Next steps (in priority order)

1. [ ] `<concrete step, with file and action>`
2. [ ] `<...>`
3. [ ] `<...>`

**Known pending items / not yet implemented:**
- `<...>`

---

## 10. ⚠️ Problems, blockers and pitfalls

| Problem | Symptom / error | Known cause | Solution or status |
|---------|-----------------|-------------|--------------------|
| `<...>` | `<...>` | `<...>` | `<...>` |

**What did NOT work (don't repeat):**
- `<attempt> → <why it failed>`

---

## 11. Open questions for the user

- [ ] `<question that needs a human decision>`

---

## 12. Free notes

`<any extra context that didn't fit above>`

---

## 13. Session log

| Session | Date | AI | One-line summary |
|---------|------|----|------------------|
| 1 | `<...>` | `<...>` | `<...>` |
