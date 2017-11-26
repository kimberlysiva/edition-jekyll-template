---
title: Intent
category: Lexicon
order: 3
header-image: /images/lexicon logo 2.png
---

Intents are the actions that follow an utterance. With the Intent asset, developers can define a set of phrases that will be used to train the intent. They can also assign required and optional entities, which will be parsed out and given to the intent handler.

Users can define a default intent handler, or there is a global handler that receives all runtime intent matches.

Intents will automatically generate a set of enums, including all the values for all the entities assigned to it. This is useful for writing intent handlers, and prevents the typographical errors that often cause issues with string matching.

![](/images/Intent.png)
