# gnawledges

A knowledge base consisting of various explorations (one per repository) for various things that were gnawing at me at the time.
Some combination of hand-written + AI assistance (especially frontend code), inspired by Simon Willison's research codebase (https://github.com/simonw/research).

Each are a public, standalone repository to keep things digestible (without much further gnawing required).
Standalone to make it easy to re-combine in future explorations ('Take the VAD code from repo X and the ASR code from repo Y and combine to make a pipeline...').

## Repositories

### 2026-05-01: Standalone voice activity detection (web) app

A not too infrequent problem that I have run into is being handed corrupted .wav files that actually have no speech in them. It would be good to have a no-frills drag-and-drop app to run voice activity detection (VAD) on someone’s laptop or locally via web app before they upload to share them. Goal was to provide someone with a dead simple drag and drop/file selection interface that would then run VAD on the selected files.

Repo: https://github.com/gnawledges/vad-check
Web app: https://gnawledges.github.io/vad-check/ 
