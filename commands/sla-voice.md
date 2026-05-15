---
description: Rewrite content in the Sovereign Leadership Architecture voice — precise, care-fronting, polarity-driven.
argument-hint: "[paste the content to rewrite, or a file path]"
---

Delegate to the `sla-voice-editor` subagent.

If `$ARGUMENTS` is a file path that exists in the working directory, instruct the subagent to read that file and rewrite its content.

If `$ARGUMENTS` is pasted content (text), pass it to the subagent as the source material to rewrite.

If `$ARGUMENTS` is empty, instruct the subagent to ask the user for the content they want rewritten — and to clarify whether they want a full rewrite, a tone pass, or specific edits.

The subagent enforces the SLA voice standards documented in `VOICE.md` and the `sla-voice-standards` skill. Do not rewrite the content yourself — delegate.
