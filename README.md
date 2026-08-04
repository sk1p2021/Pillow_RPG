# Pillow Man: Honest Haul RPG

A Godot 4 top-down 2D RPG about Pillow, a freelance art handler navigating galleries, warehouses, streets, clients, fragile objects, rent, and reputation in a fictionalized Philadelphia.

## Project goals

- Original retro-inspired presentation without copying proprietary game assets or code.
- Strong 16-bit and early 32-bit readability with modern usability.
- Modular scenes, data-driven quests, reusable artwork objects, and maintainable asset ownership.
- One complete vertical slice before large-scale content production.

## Open in Godot

1. Install Godot 4.4 or newer.
2. Clone this repository.
3. Import `project.godot` in Godot Project Manager.
4. Populate the placeholder asset folders over time.

## Organization principle

Keep files together when they change together. Character-specific sprites, scripts, audio, effects, and scenes belong inside that character's folder. Put only genuinely reusable material in `shared_assets/`.

See `docs/PROJECT_STRUCTURE.md`, `docs/ART_PIPELINE.md`, and `docs/CONTENT_WORKFLOW.md` before adding production assets.
