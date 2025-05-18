# What vibe coding taught me about vibe investing

By definition vibe coding is:

> There's a new kind of coding I call "vibe coding", where you fully give in to the vibes, embrace exponentials, and forget that the code even exists. It's possible because the LLMs (e.g. Cursor Composer w Sonnet) are getting too good. Also I just talk to Composer with SuperWhisper so I barely even touch the keyboard. I ask for the dumbest things like "decrease the padding on the sidebar by half" because I'm too lazy to find it. I "Accept All" always, I don't read the diffs anymore. When I get error messages I just copy paste them in with no comment, usually that fixes it. The code grows beyond my usual comprehension, I'd have to really read through it for a while. Sometimes the LLMs can't fix a bug so I just work around it or ask for random changes until it goes away. It's not too bad for throwaway weekend projects, but still quite amusing. I'm building a project or webapp, but it's not really coding - I just see stuff, say stuff, run stuff, and copy paste stuff, and it mostly works. @karpathy

## Implications

I've been vibe coding for a year or so. I've gotten better at it and a typical vibe coding session (simple yet effective) includes:

1. My own convention style sheet. In this sheet I specify my preference for syntax, strict rules for API request construction structure (not appending API keys to headers, using the correct ? or & symbols, etc), variable names, print to terminal x error.

2. Ingest first, ask as many questions as needed, tell me your plan, and only after getting my approval, write code. That's usually how I end my prompts.

3. Always use .env for secrets. Always use /docs for internal docs or testing. Subsequently, add them both to .gitignore. And yes, I use both files, **even though 100% of my work runs locally.**

By pinpointing and truly understanding my coding preferences, technical compromises, programming needs and most importantly, my programming profile, I created my own version of vibe coding.

I know I have a preference for camel case, modules by functionality, certain libraries over entire frameworks. I prefer sticking to the libraries I understand, even if that compromises speed (I am looking at you asyncio). I use the same API services, therefore, I know their documentation by heart. I am naturally curious, open to learn, and in that learning I end up arriving (most of the time) to the same conclusion: the basics work just fine.

I won't deny there is the pleasant discovery once in a while: Digital Ocean over AWS, streamlit, WSL, sparrow wallet.

In short: my coding sessions are predefined by a well-structured list of constraints (convention sheet), understanding of my own compromises, and taking simple elements from scalable systems (seperate config from code)<sup>1</sup>.

It got me thinking that I apply the same robotic-style

## Appendix

<sup>1</sup>: My workflows are faster by not hardcoding any secrets. It makes it easier to re-use functions and rotate my expired API keys.


