---
title: Introduction
category: Lexicon
order: 0
header-image: /images/lexicon logo 2.png
---

Mixspace Lexicon is a Unity extension for developing conversational speech commands. It is motivated by the need for more varied and accurate input in augmented, mixed, and virtual reality applications.

Lexicon currently utilizes the IBM Watson Speech-to-Text and Conversation services. Watson Speech-to-Text is ideal for this extension because of the per-word timestamps it provides. These can be used to correlate spoken words with objects (both real and virtual) that the user interacts with.

Watson Conversation is used to provide flexibility in the commands a user can say. Traditionally, voice commands have been very rigid, requiring a short clipped phrase and a robotic sort of interaction. With Watson Conversation we can turn a loose verbal request into a set of intents and entities that can be parsed by the system.

Lexicon provides a set of Unity assets that a developer can use to train the Watson Speech-to-Text and Conversation services directly from Unity. This allows for a very fast prototyping environment with minimal errors. It also allows developers to create reusable intents (with handlers) that can be used across multiple applications or shared with others. 
