# How do I make a video with Claude Code?

Connect Claude Code to Tonpit over MCP and it directs the whole production: script, footage, animation, voice, music and the cut, on a timeline you both work in. This 25-second ad took about two hours, eight footage drafts and about $25.

The full write-up, with the finished ad, the frames and every step: [How do I make a video with Claude Code?](https://www.tonpit.com/blog/how-do-i-make-a-video-with-claude-code) on tonpit.com. This repo holds the method: the setup, a brief template, and the prompts from that production, ready to copy.

Claude Code can make a video without Tonpit. It improvises: footage from one model's API, music from one site, sound effects from another, all rendered together at the end. After that, every change, a cut moved by half a second or a quieter track, means rebuilding the render. Higgsfield's connector for Claude, a popular alternative, generates footage, images and voice, but lists no timeline, music or sound effects, so the cut happens in other software.

Tonpit puts all of it in one place an agent can work in: a non-destructive timeline you and Claude share, animation written as code at no cost, libraries of music and sound effects, and the craft of video production written into skills Claude loads the moment it connects, so it can lead every stage from script to mix. If you're serious about the result, or plan to iterate or make more than one video, this is the professional way to do it.

## The twelve steps

1. **What do you need before you start?** A subscription to Claude, or to whichever model you work with, and a Tonpit account. Connecting Claude is one click; any other agent can connect itself. [SETUP.md](SETUP.md). Use a strong model: Fable 5.1 for the concept and the script, Opus 5.5 for editing and animation.
2. **Can Claude Code make a video on its own?** Yes, by improvising. Remotion and HyperFrames are free and good for animation; for the rest, Claude stitches together whatever it can reach into one render. The cost shows up in the iterations: a render is not an editing project, so every round of notes means rebuilding. Tonpit is built for that loop.
3. **What does the first prompt say?** What the video is for, and where Claude can learn about the product. Or start from a template and fit your product into it. Invest in the script. [prompts/01-opening-prompt.md](prompts/01-opening-prompt.md), [BRIEF_TEMPLATE.md](BRIEF_TEMPLATE.md).
4. **Which model do you generate with, and why the expensive one?** Seedance 2.5: it may be the cheapest way to a professional result, because it takes fewer iterations. Drafts at 480p; finish the kept shots in 1080p once the edit is locked. Animation is written as code, costs nothing, and anything in it can become a control instead of another prompt.
5. **What do you generate first?** Reference images for everything that must stay the same across shots: the character, the location, the product. [prompts/02-reference-images.md](prompts/02-reference-images.md).
6. **How do you write the shots and give notes?** Describe exactly what you imagine. When a draft is wrong, ask for a rewrite from scratch, never a patch. The drafts are also how you find out what you want. [prompts/03-shots.md](prompts/03-shots.md), [prompts/04-notes-and-rewrites.md](prompts/04-notes-and-rewrites.md).
7. **When do you build the timeline?** Early, while the footage generates. Every first cut is bad, and that is its purpose: it gives you the first feel of the rhythm.
8. **Why is the first cut bad, and who fixes it?** Because Claude can't edit yet, so the fix is your judgment. Get the rhythm right before polishing, and let the script change when you see it.
9. **How do you get the animation to look professional?** Rounds of notes, and one prompt that makes Claude review its own work as a motion designer would. [prompts/05-step-back-design.md](prompts/05-step-back-design.md).
10. **How do you add music and mix it?** Ask Claude to do the sound, and it knows what to do. Be specific when you know what you want. Fit the song by its ending. [prompts/06-music-and-mix.md](prompts/06-music-and-mix.md).
11. **How long did it take and what did it cost?** About two hours of focused work and about 2,500 credits. A credit is one cent, so that's $25. The table is below.
12. **What do you do with the finished video?** Make the next one. It goes much faster, and you have assets to reuse. Ask for versions in other lengths and ratios.

## What it cost

| What | Model | Jobs | Credits |
| --- | --- | --- | --- |
| Reference images | Seedream 5, GPT Image 2.5 | 4 | 45 |
| Footage drafts, 480p | Seedance 2.5 | 8 | about 1,100 |
| Footage finish, 1080p | Seedance 2.5 | 2 | 1,367 |
| Voiceover | Chris, two versions | 2 | 12 |
| Animation, timeline, music | written as code, free | | 0 |
| **Total** | | | **about 2,500** |

A credit is one cent. The drafts are where the learning cost; usually fewer are needed. Animation, the timeline and the music cost nothing, because a connected agent's work in the studio is free. Credits go to generated footage, images and voice. Exports come with a plan, three a month without one. Current prices: [tonpit.com/pricing](https://www.tonpit.com/pricing).

## What is here

| Path | What |
| --- | --- |
| [SETUP.md](SETUP.md) | Connecting Claude Code (or any MCP client) to Tonpit |
| [BRIEF_TEMPLATE.md](BRIEF_TEMPLATE.md) | The brief to hand Claude for a before/after ad, with the Jerv brief filled in |
| [prompts/](prompts/) | The prompts from the Jerv production, in order |
| [script/jerv-script.md](script/jerv-script.md) | The final narrator script and the shot plan |
| [video/](video/) | The finished ad, 25 seconds |

## The production, in brief

Jerv is an imaginary client-management app for freelancers. Its agent chases invoices so the freelancer does not have to. The ad is a classic before/after: a question over the moment that hurts, the product named inside five seconds, its one job shown as abstract animation, the same life after it, a call to action. Two live-action shots (Seedance 2.5), four motion pieces written as code, one narrator, one library track, 25 seconds.

Made October 26 to 28, 2026, by Itay Rose Ari with Claude Code (Opus 5.5 for most turns, Fable 5.1 for the script) connected to [Tonpit](https://www.tonpit.com) over MCP. The method (references first, rewrite instead of patch, cut early, fit the music by its ending) works anywhere; the loop is fastest where Claude and you share one timeline.
