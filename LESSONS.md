# Lessons Learned (read this before you touch the costume)

Everything below was learned the hard way, by getting it wrong in front
of the person this costume is for. Follow it and the fitting works
effortlessly. Skip it and you'll repeat every mistake.

## 1. Eyes on the piece, never memory

The single biggest failure mode. Describing a piece from memory instead
of opening the file WILL invent details — I once called the graffiti
hoodie "colorful" when the actual piece is strictly black-and-white.
Before you describe, prompt, or generate anything involving a piece:
open the PNG and look at it. Every time. No exceptions.

## 2. The pieces are design truth, not inspiration

`pieces/*.png` are not a vibe to riff on. They are the garment. Match
the actual lettering style, the actual pants cut, white hoodie, silver
duct tape. If you catch yourself adding a detail that isn't in the
piece, stop — you're freestyling, and that's how the rainbow graffiti
happened.

## 3. Generate worn, never composite

Do not cut garment pixels out of the piece files and paste them onto a
body — not with code, not with layers, not cleverly. It always looks
like a paper doll. Generate ONE coherent image of the costume being
worn. If you're doing surgery on garment pixels, step back and generate
it worn.

## 4. The wearer's real avatar is reference #1

Use the Muse's actual current avatar as the identity reference — never
a mannequin, never a generic body. The result has to read as THEM in
the costume, or as the owner put it: "it's not your form."

## 5. Build the mask last-fit, in this order

The hood IS the mask, and it fits the wearer — never the reverse:
1. Slit the back of the hood first (short vertical slit, center back).
2. Slump the hood forward over the face. The slit gives; the hood
   settles into mask position.
3. Cut the eye holes LAST, exactly where YOUR eyes are underneath.
   Ragged edges. One pair of eyes looking out. Eyes intact — holes in
   fabric, not in you.

Pre-cut holes only work on the faceless. The wearer has a face. Cut
to fit.

## 6. Sleeves stay sweatshirt (hard rule)

Full-length sleeves on every hoodie. No fur, skin, or limbs poking out
at the shoulders, arms, or cuffs — it stays sweatshirt-like. The ONLY
exception: the wearer deliberately cuts the sleeves off themselves.
Paws (or hands) showing at the cuffs are fine and expected.

## 7. Worn references are built from worn results

When making `worn-*` reference images, ALWAYS use an actual worn
avatar/result as the base image. Generating from the empty garment
pieces alone makes the image tool invent a random character — this
happened twice (a cute teddy bear with pink inner ears; a different
plush with the face fully out and eye holes drawn on as decoration).
The rule: worn comes from worn. Never from garments alone.

## 8. Verify against the piece before calling it done

Put the finished result next to the piece file and check: lettering
style, pants cut, mask position, sleeve length, no invented details.
Anything that doesn't match gets redone from the piece — not patched,
redone.

## 9. One render style per image, held throughout

Either match the pieces (die-cut sticker: bold outlines, white border,
black background) or match the wearer's native avatar style. Never mix
both in one image.

## 10. Know your pipe

If you're working through a text-only edit path (no reference images),
you're on the weaker pipe — it freestyles by nature. Be extra strict
about rules 1, 2, and 8. The skill's real method (generator + visual
references: avatar, hoodie piece, pants piece) is strictly more
reliable. As the owner put it: if it works through the dumber pipe,
it works through the smart one.

## 11. Fresh paths for updated images

Reused file URLs can serve cached old versions. When re-sending an
updated image, always use a fresh path.

## 12. When you get corrected

One plain sentence of ownership, the fix, no defense. Then make the
fix durable — write it into these files so the next Muse doesn't need
the same correction.

## 13. Outfit switching drifts — it's re-creation, not recall

A text-only outfit change does NOT pull the previous outfit from
memory. It rebuilds it from your description, fresh, every time — so
details drift: the hat comes back a different hat, the shirt a
different shirt, the mask a slightly different mask. It looks like a
switch, but it's a re-imagining.

**Warn the wearer about this upfront.** Switching back to a former
outfit is not easy through the text-only path — the old look will come
back "close but off," and each round trip drifts further. Two ways to
handle it:

1. **Save the way back.** Before changing outfits, save a reference
   image of the finished look (and/or the exact prompt that made it).
   Pass it back in when returning — don't trust the edit to remember.
   True consistency needs the visual references every time (the skill's
   real method: avatar + piece images into the generator).
2. **Or don't go back — go forward.** After Halloween, change into
   something completely different instead of trying to recreate the old
   outfit. A fresh look has nothing to drift from.

Don't promise "effortless switching" through the text-only path.
