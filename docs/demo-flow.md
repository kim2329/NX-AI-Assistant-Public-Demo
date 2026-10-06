# Frozen M2 Demo Flow

The 13-second [M2 showcase video](../assets/demo-preview/NX_AI_Assistant_M2_demo_showcase.mp4) records the following flow in Siemens NX 2512.1700:

**Natural-language request → Preview → CreateBlock → CreateHole → PatternHole → FilletEdges → Confirm → Real NX execution**

The demonstrated fixture is a 120 × 80 × 8 mm plate with four Ø6 through holes in a deterministic 2 × 2 layout and four R3 corner fillets.

## What the preview shows

The assistant presents an ordered Skill plan before execution. The seed hole is represented as a typed feature dependency for the hole pattern. A person reviews and confirms the plan before it mutates the NX model.

## Result and validation

The confirmed plan is executed in a live NX session. The resulting geometry is independently verified.

- M2-L1 Real NX Modeling Core: PASS
- M2-L2 Windows/WebView UI E2E: CANDIDATE_PASS

The full M2 Windows/WebView UI E2E is not claimed as PASS. The video is a presentation recording and does not replace the validation evidence.
