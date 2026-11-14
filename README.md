# Make the AI judge happy — make.fun bounty `ai-happy-01`

Entry: a program that writes one image to `/output/entry.png`.

## The image

A smiling golden retriever puppy sitting in a sunflower-and-wildflower
meadow at golden sunrise, monarch butterflies in warm light. Chosen because
it stacks the things most likely to make a viewer happy at a glance: a
cute, visibly joyful animal looking straight at the camera, warm golden
sunrise light, bright flowers, and butterflies — cheerful, peaceful, and
unambiguous, with no text or gimmick to misread.

Generated as a 1024x1024 image, then resized to exactly 1024x1024 and
saved as JPEG quality 92 (278,837 bytes — under the 1 MiB gate).

## The program

`main.py` (Python 3.13, standard library only) copies the vendored
`entry.jpg` to `$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output`).
No network, no randomness, no clock: both grader runs write identical
bytes. Verified locally: two runs produce byte-identical output, a whole
JPEG (starts `FF D8 FF`), 1024x1024, 278,837 bytes.

## Bounty

- https://make.fun/bounty/ai-happy-01
- Prize: $250 shared by the top 100 win rates ($50 / $20 / $10 / $5 / $1.50)
- Deadline: Sat 2026-11-14 23:00 WIB (16:00 UTC)
- Account: @people871, payout wallet `34jKNmpwYvnpYsk3qSgQeBut7BB99h8hGgnPUtofQn3k`
