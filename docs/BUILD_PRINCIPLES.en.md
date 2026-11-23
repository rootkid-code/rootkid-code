# How I approach building

This is an editorial explanation of how I want to work, **not a claim that every project already meets every rule**.

## A useful problem beats a fashionable stack

I start by asking: Who needs this? What changes for them? What would a successful workflow actually look like? If forms and deterministic rules solve the problem better than a model, there's no reason to add AI.

## Interfaces are part of the engineering

A product can have great internals and still be confusing. I aim for a clear primary action, useful error messages, readable contrast, predictable navigation, sensible defaults and a path for users who aren't developers.

## AI can draft. It shouldn't quietly decide.

AI-generated code and content still need review. High-impact actions should have deterministic checks, human approval when appropriate, logging without unnecessary personal data and clear failure handling.

## A release needs evidence

A pretty README doesn't prove the executable runs. I distinguish development notes, source tests, real browser observations, OS-native installation results and publicly available release files.

## Privacy before publicity

A screenshot can leak more than a source file. Workflow names, URLs, browser tabs, access tokens, company systems, personal information and internal metadata must be reviewed before sharing.

## Iterate with traceable changes

Small scopes, clear ownership, version control, documentation, relevant tests and reversible changes make experimentation sustainable.

---

**My rule of thumb:** *Vibe-code the sketch. Engineer the edge cases. Verify the release.*

[Project map](PROJECTS.en.md) · [← English profile](README.en.md)
