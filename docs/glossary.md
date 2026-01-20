---
title: Glossary
---

#### Stage
A collection of entities that are to be loaded, others may call it a "map", "scene", "level", etc. Stages help you build out your map in "stages", they can be merged together at runtime. *The term "Stage" is also a throw-back to what we would call maps/levels for games in the 90s*

#### Template
A singular entity, it's transform, shader data, any entity data attached to it, and all of the child entities likewise. In other environments people would call these "prefabs" or "blueprints". When a template is updated, all usages of the template across the game are updated as well.

#### Table of Contents
A collection of content ids that are grouped together for easy referencing. You can use a friendly `string` name to access various content found in the table at runtime. This can help reduce the need to have `const` string ids to content in your game code.
