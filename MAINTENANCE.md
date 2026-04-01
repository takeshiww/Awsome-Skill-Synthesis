# Repository Maintenance Guide

## Purpose

This repository is a lightweight curated list of resources about skill synthesis for agentic intelligence. The primary artifact is `README.md`, and maintenance work should stay focused on improving that list with relevant, high-signal additions.

## Current Structure

The curated list is currently organized by where skills are synthesized from:

1. Dialogues
2. Responses / Trajectories

Preserve the existing structure unless a new cluster of resources clearly justifies a new section.

## What to Include

Add an item only when it is directly relevant to skill synthesis, skill discovery, skill distillation, or skill library construction for agents.

Strong candidates usually have at least one of these properties:

- They synthesize or distill reusable skills from interaction data, responses, trajectories, or experience.
- They introduce a framework, dataset, or benchmark specifically tied to skill acquisition or skill reuse.
- They are recent and concrete enough to help readers track the state of the field.

Prefer entries with:

- A public paper link.
- A public code link when available.
- A one-line description that explains the main contribution in plain language.

## What to Exclude

Do not add papers that are only loosely adjacent, such as:

- General agent training without an explicit skill synthesis component.
- Broad planning, memory, tool-use, or RL work that does not produce or refine reusable skills.
- Opinion pieces, low-detail announcements, or duplicate mirrors of the same work.

## README Editing Rules

- Keep the current Markdown and formatting style consistent.
- Place entries in the most appropriate section.
- Order new items by relevance and recency without rewriting the entire list.
- Keep descriptions concise and specific.
- Avoid duplicate papers, duplicate code links, or repeated claims across sections.

## Weekly Update Workflow

1. Search for recent work related to skill synthesis, skill discovery, agent skill libraries, and reusable agent skills.
2. Review candidate papers and repositories for direct relevance.
3. Filter out tangential or duplicate entries.
4. Update `README.md` with only high-confidence additions.
5. Create a focused branch and commit message for that weekly batch.
6. Open a PR that summarizes what was added and why it fits the repository.

## PR Quality Bar

Open a content PR only when the weekly scan finds at least one high-confidence addition. If nothing strong is found, record the scan outcome in the automation inbox instead of opening a low-signal PR.
