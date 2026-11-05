# Prompt submission format

- **Title and category:** Short title and intended creative goal.
- **Prompt:** Full text with reusable variables in [BRACKETS].
- **Variables:** Explain what should be replaced and useful constraints.
- **Mode:** Text-to-image or reference-based editing; list required references.
- **Validation status:** Untested, or tested with the exact model/version and generation date.
- **Settings:** Aspect ratio, resolution, seed, guidance, and other available parameters. Mark unavailable settings as unknown.
- **Preview:** Optional result you have permission to publish. Label it AI-generated. Do not include private faces or data without authorization.
- **Limitations:** Common failures, necessary edits, and what was not checked.
- **Source and license:** Confirm original authorship or provide the source, license, and attribution for the prompt, references, and preview separately.

For `prompts.json`, preserve the existing fields and unique kebab-case IDs. Set `validation_status` to `untested` and `tested_models` to an empty array unless there is actual recorded testing. For a tested contribution, add a linked Markdown test record containing the details above before changing those fields. Validate JSON syntax before opening a PR.
