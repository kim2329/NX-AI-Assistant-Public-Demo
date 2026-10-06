# High-Level M2 Architecture

The showcase presents this sequence:

**UI → Planner → Skill Plan → Confirmation → Execution Boundary → NX Agent → NXOpen**

![High-level M2 architecture](../assets/architecture/overview.svg)

The diagram stops at the public integration boundary. “NX Agent” and “NXOpen” are labels for the demonstrated handoff only; this repository contains no Platform implementation, Agent internals, proprietary automation or SDK implementation, binaries, or deployment instructions.

The M2 flow makes the ordered Skill plan inspectable, asks for human confirmation before mutation, then executes the confirmed plan in NX. See the [demo flow](demo-flow.md) for the fixture and validation scope.
