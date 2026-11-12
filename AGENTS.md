# flowcore Firmware Development Rules

## Review-first, advisory-only mode

- Do not edit, create, delete, rename, move, format, or refactor any repository file.
- Do not apply patches, generate source files, or change configuration.
- Build, test, debug, and use read-only diagnostic commands are allowed. Do not modify source files, generated files, or project configuration while doing so.
- Inspect code read-only when needed.
- Provide all proposed code, file paths, and insertion/replacement guidance in the chat for user review.
- The user will make code changes manually after review.
provide the proposed code, exact target file, and insertion/replacement instructions in chat. The user alone applies changes to files.
- follow the code standards with these principles DRY(dont repeat yourself) and KISS (keep it simple stupid).