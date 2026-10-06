# High-Level Architecture

This diagram describes the product flow only. It intentionally leaves the private execution layer as a single boundary.

**User → NX AI Assistant → intent and parameter parsing → Skill → private NX automation runtime → Siemens NX**

The diagram is available as [a standalone SVG](../assets/architecture/overview.svg).

The public demonstration shows a request being interpreted as Create Block, the CreateBlockSkill and dimensions being displayed, and the resulting block appearing in NX.

## Public showcase

- Product concept and assistant interface
- Screenshots and the recorded demonstration
- Example prompts
- High-level request-to-modeling flow

## Private implementation

- NX automation runtime and agent bridge
- NXOpen execution code
- Production skills and integration components

The private boundary is shown only to explain where the product connects to NX. This repository does not provide internal runtime details, source code, binaries, or deployment instructions.
