---
title: Runtime
category: Lexicon
order: 5
header-image: /images/lexicon logo 2.png
---

The Lexicon Runtime is a MonoBehaviour that controls the runtime communication with the Watson cloud, parsing results, and triggering intent actions. It takes a single Workspace, and provides a variety of settings for confidence thresholds, etc.

Keywords for Speech-to-Text can be added here or at runtime. This is useful for detecting words that can be processed immediately (e.g. “here”) or for adding additional words at runtime.

The Lexicon Runtime includes a few events that developers can register handlers for:
* OnSpeechToTextResult: full speech-to-text results (including interim results)
* OnKeywordDetected: speech-to-text keyword detected
* OnLexiconResults: all results from speech-to-text and conversations services correlated and timestamped
to match the actual runtime each word was uttered

![](/images/Runtime.png)
