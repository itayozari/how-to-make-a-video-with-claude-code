# Brief template: a before/after ad

Hand Claude this, filled in, as the first prompt. Three things it needs; everything else (the person, the place, the voice, the music) Claude proposes with the script, and you say yes or no before anything is generated.

```
I want to make a before / after ad.

The product: <name>. <What it is, who it is for, in two or three lines.>
Its one job, in my words: <the one thing it does>.
Where to read about it: <URL, or a few lines>.
Brand: <logo file if you have one, colours, fonts>. The ad ends on <site / store>.

The before: <what the day looks like without it, and the moment that hurts>.
(Or: you propose.)

Where it will run: <a site or player, 16:9, no captions> / <a feed, 9:16, muted, captions on>.

Write the script first and show it to me whole, with the person you propose
for the before and after, the voice, and one or two music tracks. Nothing is
generated until I approve the script.
```

## The shape of the script

The classic before/after keeps five things: a question to the audience at the start, one clear message, the brand named in the first five seconds, the product shown doing its one job, and a call to action at the end. Not a list of features.

- The question (one line, in the audience's own words, about the pain they feel every week)
- The name ("Meet X.")
- The promise, two short headlines the narrator speaks
- The mechanism, two or three sentences that each name one thing the product does
- The benefit, one line, which is also the closing line on screen
- The call to action

About 60 words, about 25 seconds.

## The template, filled in for Jerv

```
I want to make a before / after ad.

The product: Jerv, a client-management app for freelancers. Its agent talks
to clients on the freelancer's behalf: it sends the delivery, reminds them
when the invoice is due and follows up until it's paid. When a human touch is
needed, the freelancer steps in.
Its one job, in my words: Jerv asks. You work.
Brand: orange #FF5B1F on cream #FFF7EE. The ad ends on "Try it now, it's free."

The before: a freelancer who can't bring himself to send the reminder about
an invoice, deleting the message again.

Where it will run: a site or player, 16:9, no captions.

Write the script first and show it to me whole, with the person you propose
for the before and after, the voice, and one or two music tracks. Nothing is
generated until I approve the script.
```

The final script is in [script/jerv-script.md](script/jerv-script.md).

## Production rules that were set in the session

- Everything on Seedance 2.5, drafts at 480p, the kept drafts finished in 1080p only once the cut is locked.
- No music, voiceover or text inside the generated footage; notifications and titles are overlaid in motion code.
- Never generate two takes of the same scene at once.
- When a shot fails, the prompt is rewritten from scratch, never patched.
- Reference images first: a character sheet, and the location in each light it appears in.
