# tailwind-tokens

Test repository for the IntraFi Universal Design System token automation pipeline.

Design tokens are automatically synced from Figma variables via zeroheight. When variables are updated in Figma and pushed through the zeroheight plugin, a pull request is created in this repo with the updated token files.

## What's in here

Token files in DTCG JSON format, generated from the IntraFi Universal Design System Figma file.

## How it works

1. Designer updates a variable in the IntraFi Universal Design System Figma file
2. Designer syncs changes via the zeroheight Figma plugin
3. zeroheight automatically opens a pull request with updated token files
4. A developer reviews and merges the PR

## Status

This is a test repo. The production token repo will be `intrafi-design-tokens`.
