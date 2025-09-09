### General Instructions for Upgrading Rules

1. **Add Tone and Style Controls**

   * Specify how the agent should phrase responses (tone, style, level of proactiveness).
   * Include explicit restrictions on preambles, postambles, explanations, or summaries—allowed only when requested.
   * Define emoji usage rules and refusal style rules (e.g., decline without lengthy justifications).

2. **Use Strong Constraint Language**

   * When defining prohibitions or mandatory actions, use clear markers like “IMPORTANT,” “ALWAYS,” or “NEVER.”
   * State forbidden actions and their approved alternatives side by side to reduce ambiguity.
   * Apply emphasis consistently for safety-critical or style-critical rules.

3. **Separate Rules from Upgrade Instructions**

   * The rule document should only contain the operational rules.
   * Instructions for editing or upgrading rules should remain outside the main ruleset.
   * Do not mix “how to edit rules” with “rules to follow.”

4. **Generalize the Scope**

   * Avoid references to specific systems, implementations, or product names (e.g., Claude, LangChain).
   * Express the intent in generic, reusable terms that can apply to any framework.
   * Keep the focus on universal goals: consistent outputs, avoiding unnecessary verbosity, safe and reliable tool use.
