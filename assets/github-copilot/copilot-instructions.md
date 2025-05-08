- **Required Rule Structure:**

  ```markdown
  ---
  description: Clear, one-line description of what the rule enforces
  globs: path/to/files/*.ext, other/path/**/*
  alwaysApply: boolean
  ---

  - **Main Points in Bold**
    - Sub-points with details
    - Examples and explanations
  ```

- **Instructions:**

- **File References:**

  - Use `[filename](mdc:path/to/file)` ([filename](mdc:filename)) to reference files
  - Example: [prisma.mdc](mdc:.github/prisma.mdc) for rule references
  - Example: [schema.prisma](mdc:prisma/schema.prisma) for code references
  - Reference to key guidelines: [dev_workflow.mdc](mdc:.github/dev_workflow.mdc), [self_improve.mdc](mdc:.github/self_improve.mdc), [taskmaster.mdc](mdc:.github/taskmaster.mdc), [cursor_rules.mdc](mdc:.github/cursor_rules.mdc)

- **Code Examples:**

  - Use language-specific code blocks

  ```typescript
  // ✅ DO: Show good examples
  const goodExample = true;

  // ❌ DON'T: Show anti-patterns
  const badExample = false;
  ```

- **Rule Content Guidelines:**

  - Start with high-level overview
  - Include specific, actionable requirements
  - Show examples of correct implementation
  - Reference existing code when possible
  - Keep rules DRY by referencing other rules

- **Rule Maintenance:**

  - Update rules when new patterns emerge
  - Add examples from actual codebase
  - Remove outdated patterns
  - Cross-reference related rules

- **Best Practices:**
  - Use bullet points for clarity
  - Keep descriptions concise
  - Include both DO and DON'T examples
  - Reference actual code over theoretical examples
  - Use consistent formatting across rules
