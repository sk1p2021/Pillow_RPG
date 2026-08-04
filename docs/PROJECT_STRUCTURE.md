# Project Structure

This repository uses a hybrid feature-based layout. Files live near the scenes and systems that own them; only truly shared resources belong in shared libraries.

```text
addons/
autoload/
core/
actors/
  pillow/
  npcs/
  bosses/
  enemies/
  hazards/
objects/
  artworks/
  packing/
  tools/
  furniture/
  vehicles/
  interactables/
locations/
  overworld/
  interiors/
  exteriors/
  galleries/
  warehouses/
  streets/
gameplay/
  cargo_handling/
  inspection/
  dialogue/
  inventory/
  quests/
  jobs/
  economy/
  reputation/
  skills/
  encounters/
  tutorials/
ui/
data/
shared_assets/
source_art/
tools/
tests/
docs/
scenes/
scripts/
```

## Ownership rule

Keep files together when they change together. A production character folder should contain its scene, script, data, sprites, portraits, effects, and audio.

## Naming

- Files and folders: lowercase `snake_case`
- Scene node names: `PascalCase`
- Stable content IDs: lowercase `snake_case`
- Do not use `final`, `final2`, or personal initials in runtime filenames.

## Empty folders

Git does not store empty directories. Every placeholder directory contains either a README or `.gitkeep`. Replace those files when real content is added.
