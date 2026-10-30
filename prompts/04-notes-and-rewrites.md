# 04 · Notes, and the rewrite instead of the patch

## The rule

Models fix notes as patches. They bolt your note onto the existing prompt, and with every round the prompt gets less coherent and the shot gets worse. Ask for a rewrite instead:

```
Don't patch the prompt. Read my notes, rebuild the shot in your head from scratch, and write a new prompt as one coherent description: where everything is, what the camera does, what he does. Keep nothing from the old prompt that the new picture doesn't need.
```

## The notes that led to the two shots

Eight drafts at 480p. These are the notes, in order, as plain instructions:

1. **One take per scene.** Don't generate two versions of the same shot at once; judge one, then decide.
2. **Say the camera exactly.** A low angle from the phone toward his face, the phone in the foreground, the camera on his left. Name the lens in millimetres; "wide" alone is not a lens.
3. **Play it smaller.** The first performances were overacted. "His eyes and his breath, nothing more."
4. **Fix the geometry before the acting.** In two drafts he sat behind the desk with the monitor cutting through his body. The prompt had never said where the desk, the monitor, the window and the camera stand relative to each other.
5. **Less is more.** Generating stills of every frame first was rejected: a precise prompt does better than a long one. Lines that described a feeling instead of something the camera sees were cut ("through his nose", "his shoulders drop", "its glow flickers on his chin").
6. **Pull the lens look back.** A characterful lens made the shot look unrelated to the rest. Cinematic, 35mm, nothing more.
7. **Change the angle, not only the words.** The pull-back started too straight on, so the back of the monitor filled the frame. Start on his face, smiling, focused, and pull back along a slight diagonal, the monitor entering from frame left.

The next draft was the keeper. The approved prompts are in [03-shots.md](03-shots.md).

## What the drafts taught

- They are not only attempts at the right shot. They are how you find out what you want: a camera move planned at the start didn't work, one long shot became two, and the ad found its shape in the edit.
- Geometry first, acting second.
- A lens is a number.
- Cut every line the camera cannot see.
- Judge at 480p. Finish only the draft you keep.
