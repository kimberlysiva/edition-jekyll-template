---
title: Entity
category: Lexicon
order: 2
header-image: /images/lexicon logo 2.png
---

Developers can create Entity assets directly in the Unity editor. Entities can have a variety of binding types, e.g. colors, models, textures, animations, etc. Users can extend the LexiconEntity class to create their own data bindings. When appropriate, these bindings can be assigned or dragged-and-dropped directly in the editor.

The user can also assign synonyms to each entity value.

Note that multiple entities can have the same Entity Name, and their values will be automatically merged. This is useful when an entity can have different meanings depending on the intent, e.g. Color might be a color value for primitives but a texture value for models.

![](/images/Entity.png)
