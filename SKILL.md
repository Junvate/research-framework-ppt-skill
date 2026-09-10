---
name: research-framework-ppt
description: Create or revise editable PowerPoint research framework diagrams from project descriptions, proposals, technical routes, related-work documents, or cross-topic interfaces. Use when the user needs a scientific research architecture, technical framework, workflow, layered system, task relationship, or validation loop rather than a marketing presentation.
---

# Research Framework PPT

Turn research content into a compact, editable technical diagram whose logic is visible at a glance. Use the Presentations skill for PowerPoint authoring and validation.

The retained reference deck is one example of an input, core mechanism, output, and feedback layout. It is not the mandatory structure for every request.

## Select The Structure

Read [framework archetypes](references/framework-archetypes.md) before choosing a layout. Select the archetype that matches the dominant relationship in the source content:

- containment or dependency favors a layered architecture;
- temporal or procedural dependency favors a workflow or closed loop;
- upstream inputs, a central mechanism, and downstream outputs favor an input-core-output framework;
- research questions linked to methods and evidence favor a problem-method-result framework;
- several topics exchanging capabilities favor a task-interface map.

Use one primary structural grammar per slide. Combine at most one secondary relationship, such as an outer feedback loop, when it materially improves the explanation.

## Build The Content Model

Extract only source-backed elements:

1. Research object and scope.
2. Problems, challenges, or scientific questions.
3. Inputs, data, knowledge, constraints, and upstream capabilities.
4. Core mechanisms, technical modules, workflows, models, and tools.
5. Outputs, metrics, deliverables, validation methods, and downstream interfaces.
6. Feedback, iteration, human review, uncertainty, or governance constraints.

Express the main chain as `input -> operation -> output` or `cause -> mechanism -> result`. Preserve official terminology and distinguish facts, hypotheses, proposed methods, and expected outcomes.

## Draft Slide Copy

- Use short noun phrases for titles and modules.
- Keep each box focused on one responsibility or result.
- Put detail in one concise supporting line rather than shrinking a paragraph into a box.
- Use the user's exact project names when relationships among topics matter.
- Do not invent technical indicators, performance numbers, interfaces, or causal claims.
- Show uncertainty, evidence, counterevidence, and validation conditions when they affect the conclusion.

## Create The Presentation

- Follow a user-supplied presentation template when provided.
- Otherwise, use [the style system](references/style-system.md) and `assets/reference-framework.pptx` as visual guidance.
- Keep diagrams editable with native PowerPoint shapes, text, and connectors.
- Route connectors around text. Put long feedback paths along the outer edge of the framework.
- Preserve a clear visual hierarchy: slide title, one-sentence purpose, section labels, modules, and constraints.
- Default to one framework slide when the user asks for a framework diagram. Do not add a cover unless requested.
- Do not add organization names, institutional marks, or branding unless the user explicitly supplies and requests them for the current deliverable.

## Validate

Render every output slide and inspect it at full size. Confirm:

- the chosen archetype matches the research logic;
- all requested topics and interfaces are present;
- labels remain readable without overlap or clipping;
- arrows communicate the intended direction;
- feedback loops do not cross core module text;
- the deck remains editable;
- no unrequested branding appears.

Use `assets/preview.png` only to understand the reference layout. Do not place the preview image into the final presentation.
