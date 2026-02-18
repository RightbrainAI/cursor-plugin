# Rightbrain Tasks — Cursor Plugin

Manage [Rightbrain](https://rightbrain.ai) AI tasks directly from Cursor.

## What is Rightbrain?

Rightbrain lets you embed AI into your existing tech stack via a single API call — no infrastructure to build or maintain. The core unit is a **Task**: a stateless, versioned AI function that takes an input and returns a structured output (JSON, text, images, audio). Tasks are triggered via API, webhook, or scheduled job and return predictable results ready for your UI, database, or downstream workflow.

Tasks live inside **Projects**, which belong to **Organizations** — giving you multi-team governance, role-based access, version control, and rollback out of the box.

## What this plugin does

This plugin brings Rightbrain task management into your editor so you can iterate on AI functionality without leaving Cursor:

- **Browse** tasks across your orgs and projects
- **Run** tasks with custom inputs and inspect structured outputs
- **Create** new tasks following best-practice patterns (classification, extraction, generation, image generation)
- **Update** task configs — prompts, models, output formats, parameters
- **Export / Import** task definitions as JSON for version control and sharing

## Installation

Install from the Cursor Marketplace, or clone this repo and point Cursor at the local directory.

## Usage

Invoke the skill in Cursor's agent chat with phrases like:

- "rightbrain tasks"
- "create task"
- "browse tasks"
- "run task"

The skill walks you through authentication (via `npx rightbrain@latest login`), org/project selection, and the desired operation.

## Requirements

- Node.js >= 18
- A [Rightbrain](https://rightbrain.ai) account

## Links

- [Rightbrain Platform](https://rightbrain.ai)
- [Rightbrain Documentation](https://docs.rightbrain.ai)
- [Source Skills Repo](https://github.com/RightbrainAI/claude-code-skills)

## License

MIT
