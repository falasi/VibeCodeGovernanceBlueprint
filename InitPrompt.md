# Plan-First (print before coding)

Analyze the codebase and understand the complete implamentation and follow the full flow, Output a brief plan listing files to create/modify, the exact edits, risks + mitigations, and the unit tests you’ll add. do not start until you give me a clear picture of everything, wait for my next prompt before starting. 


1. Scope & rules
   - Production-grade fix, not a hot patch.
   - Follow scoped-change, plan-first, interface-compat, and tests-required rules.
   - Do not rename unrelated files or touch non-payments features.
   - Always follow the testing guard rails attached to this prompt.
   - Remember clean quality commented code, we have time security quality over speed.
   - New code you add or modify MUST be TypeScript (.ts / .test.ts). Do not introduce new .js source files
