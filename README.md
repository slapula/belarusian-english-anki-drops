# Belarusian/English Anki Flashcards (Drops Lexicon)

This repository manages an [Anki](https://apps.ankiweb.net/) flashcard deck that consists of words taken from the Russian lexicon of the [Drops](https://languagedrops.com/) language learning app. This is not meant to be an exact reproduction of the Drops product itself. I only created this to help me and others learn Belarusian in a way that closely resembles that experience.

## Caveats

Seeing as that Drops is a paid service, there is only so much one can do to replicate that learning experience.

- Words may be wrong or mispelled. Please feel free to submit an issue or PR to have them corrected.
- Due to the size of this deck and the relative rarity of spoken Belarusian on services like [Forvo](https://forvo.com/), the audio generated for this deck was done using a [third-party Belarusian TTS endpoint](https://huggingface.co/spaces/jhlfrfufyfn/bel-tts).  Pronounciations are an approximation and have not been validated by native speakers as of yet.
- Images were attached to each card to help the learning process however this too was "best-effort".  You may happen upon images that don't match the word or phrase and I would gladly accept PRs that replace bad images with ones more fitting.
- Drops as a service uses topic "buckets" to organize words for study.  I did my best to tag all cards with the associated topics found on Drops.  This process was not 100% perfect.  You will likely find words or phrases that are missing from topics they normally appear under.  if you find any tagging that is in need of fixing, please feel free to submit a PR. 
- No media (such as images/audio) or code was taken from Drops itself to create this deck.

## Tools & Services used to create this deck

- Python
- [Anki-Connect](https://github.com/FooSoft/anki-connect)
- [OpenAI GPT-4](https://openai.com/gpt-4)
- [Pexels](https://www.pexels.com/)
- [jhlfrfufyfn/bel-tts](https://huggingface.co/spaces/jhlfrfufyfn/bel-tts)

## How to use this deck

This repository follows the pattern for usage with [CrowdAnki](https://github.com/Stvad/CrowdAnki).  You will need to install this plugin then follow the "Import from Git" instructions: [https://github.com/Stvad/CrowdAnki#import-from-git](https://github.com/Stvad/CrowdAnki#import-from-git).

## How to contribute

For folks that are not familiar with git and/or Github: To be determined.

For folks that are: You can follow the [instructions from CrowdAnki](https://github.com/Stvad/CrowdAnki#generic-collaboration-workflow).  I'm not doing anything differently with this deck and will accept PRs based off that workflow.