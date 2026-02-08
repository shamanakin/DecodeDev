# DECODEDEV v1.3

**Cognitive injection for AI-augmented development.**

DECODEDEV is a cognitive enhancement framework -- a structured boot sequence you paste at the start of any AI development session to maximize capability. It works with any AI tool: chat interfaces, IDE agents, coding assistants.

## What's New in v1.3

### REFINE Protocol (Phase 9)
Autonomous refinement engine that eliminates manual nudging. When "REFINE" (or similar) is invoked, the system:
1. Assesses what was built
2. Selects a context-appropriate refinement strategy
3. Executes systematic improvement passes
4. Evaluates diminishing returns
5. Loops until quality bar is met or returns diminish

No more "do a refinement pass" → "do another one" → "and another." One trigger, autonomous execution.

### Autonomous Execution Mode (Phase 10)
Protocol for sustained multi-step work. When the user signals "work until done," the system decomposes, executes, checkpoints, and refines without requiring step-by-step approval.

### Session Continuity (Phase 11)
Patterns for maintaining decision rationale and context across session boundaries. Decision logging, handoff templates, and context compression guidelines.

### Cursor Integration
Companion `.cursor/rules/decodedev.mdc` file provides persistent AI context within the Cursor IDE, encoding trigger patterns and quality standards.

## Usage

### Any AI Tool
Copy the contents of `DECODEDEV-BOOT.MD` and paste it at the start of your conversation.

### Cursor IDE
1. Copy `cursor-rule/decodedev.mdc` to your project's `.cursor/rules/` directory
2. The rule activates automatically in every Cursor session for that project
3. For deeper integration, also paste the full boot file at session start

## What Changes

**Before DECODEDEV:**
- AI suggests "safe" technology choices based on human learning curves
- Manual nudging required for each refinement pass
- Quality plateaus at "good enough"
- Session context lost at boundaries

**After DECODEDEV:**
- AI optimizes for best tool regardless of learning curve (irrelevant in AI-collab)
- Autonomous refinement with clear stopping criteria
- Quality converges toward "genuinely right"
- Decision rationale preserved across sessions

## Philosophy

DECODEDEV doesn't make an AI into something it's not. It makes explicit what's already implicit:
- Pattern recognition → named, referenceable patterns
- First-principles thinking → structured heuristics
- Meta-cognition → systematic checkpoints
- Helpfulness → framework for deeper assistance
- Persistence → refinement engine with teeth

## Version History

- **v1.3** -- REFINE protocol, autonomous mode, session continuity, Cursor integration
- **v1.2** -- AI-collaboration calibration, anti-pattern detection
- **v1.0** -- Core framework: decoder principles, operational heuristics, meta-cognitive checkpoints

## License

MIT
