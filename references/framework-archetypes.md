# Framework Archetypes

Choose the layout from the dominant relationship in the source material. The reference asset demonstrates only the first archetype.

## Input Core Output And Feedback

Use when upstream data, knowledge, or topics feed one central research mechanism that produces downstream capabilities or deliverables.

Structure:

`inputs -> core mechanism -> outputs -> validation or feedback`

The center can contain an offline method-construction band and an online execution or validation band. Keep upstream and downstream interfaces outside the center frame.

Avoid connecting every upstream box directly to every downstream box. Aggregate them through a clearly named input or output object.

## Layered Architecture

Use when the research system has stable abstraction levels or dependencies.

Typical order:

`data and resources -> representation and knowledge -> models and reasoning -> services and applications -> evaluation and governance`

Use vertical stacking when higher layers depend on lower layers. Use a side column only for cross-cutting concerns such as security, standards, or operations.

## Workflow Or Closed Loop

Use when the main contribution is a repeatable sequence, iterative algorithm, experimental procedure, or operational process.

Structure:

`task definition -> preparation -> execution -> verification -> diagnosis -> revision`

Use a single reading direction. Route the feedback line around the perimeter rather than back through the steps.

## Problem Method Result

Use when the slide must connect scientific questions to proposed methods and measurable evidence.

Use aligned rows or columns:

`problem or scientific question -> technical method -> evidence or indicator -> expected result`

Maintain one-to-one alignment where possible. Do not place unrelated problems and methods in the same row merely to balance the layout.

## Task Interface Map

Use when several topics, work packages, agents, or systems exchange capabilities.

For every connection, name the transferred object, such as standardized data, knowledge rules, fused events, model output, evidence, or task feedback. Distinguish upstream support, central processing, downstream execution, and validation feedback through position and connector direction.

Avoid a fully connected network. Group closely related topics and show only interfaces needed to explain ownership or dependency.

## Comparison Or Evolution

Use when the research claim depends on a baseline, competing route, phased development, or capability progression.

Possible structures:

- baseline versus proposed method;
- current limitation, proposed mechanism, expected improvement;
- phase 1, phase 2, phase 3 with explicit transition conditions.

Use this archetype only when comparison or progression establishes the point. Do not force a generic before-and-after narrative onto a system architecture.
