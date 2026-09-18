+++
date = '2026-09-18T00:15:00-08:00'
draft = true
title = 'Learning Git by Accident'
summary = 'What my first repository actually records, and why the blog was not the point.'
tags = ['git', 'origins', 'agents']
status = 'exploratory'
+++

This site was built on February 9, 2026, and then abandoned for seven months. I came back to it tonight to find out why, and the commit history turned out to be a better record than my memory.

## What happened

I asked Sonnet whether it could help me make a blog. I had never used git, never used GitHub, and had no programming background. We used Hugo, because that is what the quickstart suggests, and picked the default theme, because I had no way to evaluate any of the others. The whole thing took thirty-eight minutes.

Here is what git recorded:

| Time | Message | What it contained |
|---|---|---|
| 15:35 | Initial site setup | the site, the theme reference, the built output |
| 15:38 | Initial site setup | `.gitignore` |
| 15:49 | first commit | one line of README |
| 16:13 | first commit | one more line of README |

Four commits. Two of them are both called "first commit," which is not a mistake — it is the commit message GitHub suggests on the page it shows you after you create a repository, and I ran through those instructions twice. I had created the repository on the website with a README already in it, which meant GitHub had a history and my laptop had a different one, and git refused to combine two histories that share no ancestor. I did not understand the error. I cleared it and started the steps again.

The `.gitignore` is dated three minutes after the files it was meant to ignore. This does nothing. Git only ignores files it is not already tracking, so writing the rules afterward has no effect on anything already committed. The generated output stayed in the repository for seven months because of those three minutes.

The author on all four commits is a name git guessed from my laptop's hostname, because I had not configured it and did not know that was a thing.

Somewhere in the middle I was taking screenshots of the GitHub settings page, because I needed a personal access token — a thing I had never heard of, that you cannot use your password instead of, and that nothing warns you about until the exact moment you are finally ready to push — and the instructions I was following described a screen that had since been redesigned.

## What I actually took from it

Not a blog. The site was never published. It had one page, and the two links on it were still placeholder text in square brackets when I found it again tonight.

What I took was this: **if code lives in a repository, and a model can act on a repository, then a model can change real software instead of showing me text about it.**

That sounds obvious written down. It was not obvious to me at 4pm on February 9, when I had known what a repository was for about half an hour. It arrived because I kept mistyping the commands. Every typo made the gap more concrete between *knowing what I wanted done* and *getting the machine to accept it*, and the obvious way to close a gap like that is to have something else type.

Which is how I started thinking about webhooks.

## Five days

Five days later I had a repository of Markdown files that an assistant could write memories into. Same structure — a folder of text with history — different contents.

That is the part I keep returning to. Markdown is not special and git is not clever. What they give you is a place where writing persists, can be read back, and carries a record of how it changed. Models have no memory between conversations; every session starts from nothing. But a file that gets read at the start of every session does the same job from the outside. The continuity is not in the model. It is in the repository.

Almost everything I have built since is a variation on that. The context workspace is a store of things worth reading again. The evaluation harness keeps prompts and responses together so a comparison can be revisited. The agent coordination protocol is mostly append-only notes that let separate agents share state without overwriting each other. Different projects, one shape.

## The pattern I did not notice

Each of those started as something manual and error-prone that I was doing by hand while learning what the pieces were. Set up the Cloudflare bindings by clicking through the dashboard. Trace a bug across five agents by reading their output. Type the git commands wrong, repeatedly.

Then it becomes software.

I do not think this is a strategy so much as a low tolerance for doing something twice. But it does mean the badly-done manual version is not wasted time — it is where the requirements come from. You cannot automate a process you have not yet done badly.

## Why the site sat

I did not publish it because I did not think anyone should read me. That was not a judgment about the writing; I had not written anything yet. It was just easier not to.

Seven months later the reason to publish is different, and better: I want somewhere to put the reasoning while it is still unfinished. The portfolio is for work that is done. This is for the part before that, where the result is still uncertain and the interesting thing is what the measurement is actually picking up.

It is fitting that the first post is about the repository itself. The commit timestamps are the only honest record of where the rest of this started, and they say plainly that I did not know what I was doing. That turns out to be the useful part.
