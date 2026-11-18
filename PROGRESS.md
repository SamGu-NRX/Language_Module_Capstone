# Progress snapshot: CogPortal-language-weight-rehearsal (20261118)

The local checkout `~/Programming Projects/CogPortal-language-weight-rehearsal` was removed on 2026-11-18 to free disk space on Sam's Mac, after everything in it was pushed here. This file records where the work stood.

## What it is

Language_Module_Capstone: Trained weights are in data/W_embed.npy (512 to 200). Re-run train.py to regenerate



## State

- Checkout branch: `main` at `8789361ad7`
- Snapshot branch: `archive/wip-20261118` (HEAD plus the uncommitted work listed below)
- Last commits:
- 8789361 2026-07-23 Made database
- 86876a3 2026-07-23 Train + Weights done
- 14d5d48 2026-07-23 Merge branch 'main' of https://github.com/LashikaKapoor28/Language_Module_Capstone into sriram
- ae70783 2026-07-23 Merge branch 'main' of https://github.com/LashikaKapoor28/Language_Module_Capstone
- a7e297e 2026-07-23 Made confusors non random and chose from top k most similar images
- f3cc22e 2026-07-23 Add COCO JSON parser and ID mappings
- c280ef8 2026-07-23 Merge branch 'main' of https://github.com/LashikaKapoor28/Language_Module_Capstone into sriram
- ee5d7ac 2026-07-23 Created MyNN model Extracted (caption-ID, image-ID, confusor-imageID) triples Used cosine similarity to find the most similar confusor image for each caption-image pair Used that similarity to create a triplet loss function Used the loss function to determine accuracy of the model

Uncommitted work captured in this branch (1 paths):

- `.DS_Store`

Git-ignored files that can't be rebuilt (.env files, local data) were copied to `~/MacSetup/worktree-leftovers-20261118/CogPortal-language-weight-rehearsal` on the Mac. They are not on GitHub or Drive.

## What's left

Nothing recorded beyond the commits above.

## How to resume

```sh
git clone https://github.com/SamGu-NRX/Language_Module_Capstone.git "$HOME/Programming Projects/CogPortal-language-weight-rehearsal"
git -C "$HOME/Programming Projects/CogPortal-language-weight-rehearsal" checkout archive/wip-20261118
```

Then copy the kept ignored files back: `cp -R "$HOME/MacSetup/worktree-leftovers-20261118/CogPortal-language-weight-rehearsal/." "$HOME/Programming Projects/CogPortal-language-weight-rehearsal/"`, and reinstall dependencies.

## Thread

No T3 thread was found for this checkout.
