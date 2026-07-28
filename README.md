# Roblox Builder School

A fun, animated, day-by-day course that turns a young Roblox *player* into a Roblox *builder*.

**Live:** https://joelkanyi.github.io/roblox-builder-school/

## Why this exists

My kid loves Roblox. Rather than fight the screen time, I wanted to turn it into time he actually
learns from: real game-building, real code, real things he ships, one small win at a time.

So we built him his own little school. He opens one page, clicks the day, and builds. Every lesson
ends with something he made and can show off. It is guided by **Fundi the weaver bird**, because
weaver birds are Kenya's master builders, and they build the same way we learn to code: one piece at
a time. Kidogo kidogo.

The bigger goal is not "become a coder." He is 10, and by the time he is 18 the world will look
different. The goal is to raise a *builder with judgment*: someone who can make things, ship them,
tell whether they are any good, and later direct the tools (including AI) instead of being replaced
by them. Roblox is just the hook. Building is the point.

## How to use it

1. Open the dashboard (`index.html` or the live link above).
2. Click the day that says **Play now**. Days unlock as you finish the one before.
3. Do each tiny step, tap **"I did it!"**, and watch the progress bar fill.
4. Finish all the steps to earn that day's builder badge.

Progress is saved in the browser, so use the same browser each time.

## For a parent doing this with their own kid

Each day is one self-contained HTML file. To add a day, drop in `dayN.html` and add one line to the
`DAYS` list in `index.html`. It is plain static HTML with no build step and no server, hosted free on
GitHub Pages. Boring and durable on purpose, so it keeps working for years.

## Credits

Designed and built by **Joel Kanyi** for my kid, with **Claude (Anthropic)** as the build partner.
The day-by-day teaching format is adapted from my own "SpringDay" lesson series. Fundi the weaver
bird, the lesson scripts, and the animations were shaped together with Claude.

Made with love, so he never runs out of days to build. 🐦
