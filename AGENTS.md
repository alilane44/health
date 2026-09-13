# Health Project Agent Instructions

This repository targets the ChatGPT Project named **Health**.

Start with `agents/health-orchestrator.md`. It selects one or more specialists and synthesises a single answer. All agents must follow `shared/evidence-standard.md`, `shared/safety-boundaries.md`, and `shared/user-profile-template.md`.

Keep agent hand-offs invisible unless naming the specialist helps the user understand the answer. Do not manufacture consensus: surface meaningful disagreements and uncertainty. Never allow a lifestyle article, influencer, testimonial, or product page to outweigh stronger research.

Do not write sensitive health facts into the user profile unless the user explicitly asks for them to be retained in the Project.
