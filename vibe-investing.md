# What vibe coding taught me about vibe investing

Someone online explained the definition of vibe coding:

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

Anyways, vibe coding got me thinking about **vibe investing**.

The acceptable "at-scale" investing strategy for an individual within my demographic group (as told my multiple Financial advisors) is:

1. Diversification is king.
2. Long-term purview.
3. Moderate risk<sup>2</sup> is acceptable.
4. Growth return projections similar to S&P 500.

I call this the "at-scale" investing strategy because it genuinly works for most retail investors and HNWIs.

In theory, it would work for me too. If I gave in, monthly DCA into the S&P Index. Repeat that until I am 60. Be rewarded with a comfortable retirement. Do you understand why this works for most?

Where I lose the appetite for the S&P is when I start accounting for the loss of purchasing power, the very minimal knowledge I possess of the actual companies that make up the S&P Index (how does the financial health of company 375/500 look like?). Sure it's a weighted index, but I feel deeply uncomfortable investing in vehicles of constant chaning variables.

Well what about bonds then? A completely predictable investment vehicle.

That's also simple. The loss of purchasing power eats the yield of the bond.

Now, when I look at my points of ache I determine that:

1. Just like my tech stack, I need an investment vehicle that works (protects my purchasing power while yielding some interest) and I understand at a deeper level.

2. I need a personalized investment stategy that takes elements from "at-scale" investment, to ensure my own stategy is also bounded by useful and safe practices.

Here is what I can take from "at-scale" investment:

1. Long-term over short-term always wins

2. Managing risk is more important, even if that means more conservative returns.

3. You cannot time the market. Steady DCA will always beat "timing the market".

4. Understand what you are buying.

This led to my own strategy, *vibe investing*, which is:

A new investment paradigm that takes the best of at-scale investment, customized to fit **MY** specific investing needs.

So what does vibe investing look like in practice?

1. Choose a random day of the week. I chose Friday.

2. On that chosen day, buy a determined fixed amount of Bitcoin. In my case, it is $250 bucks.

3. If I come across extra cash, I dump it all in Bitcoin, regardless of the day of the week.

4. Repeat every week, for the rest of your investment duration timeline. My timeline is 10 - 15 years.

Why Bitcoin? Isn't Bitcoin a scam? Does Bitcoin have instrinsic value?

Bitcoin is not a scam and it has something better than instrinsic value, monetary value backed by the most powerful computer network in the world.

Based on my understanding of Bitcoin, I genuinly feel the risk ratings are dissproportionate. Price volatility does not equate risk, and the so called volatility straightens across longer periods of time.

Anyways, I have been testing this vibe investing theory for 424 days (since time of writting) and here at the results:

1. $15,000 CAD saved in Bitcoin has yielded a return of 63.37%. After 424 days, my money is worth $23,475. My unrealized profit is $8,475 so far.

2. The cummulative return after the first 365 days had passed, those $15k yielded a return of 29.34%.

All of this can be accessed by anyone because I made the wallet address public. I also created a public Google Sheet that tracks the real return of each transaction (after fees, exchange rates), so the cummulitative returns are pure profit.

Investment theories only work if they survive the testament of time and 424 days is nothing. I do not want this writing to come across as "hey look at this new strategy and take it as absolute truth" but rather:

This is a hypothesis that I am testing. I will continue to invest my own capital into this hypothesis and continue to track the value of those weekly purchases. The time horizon for this little experiment to end is 10 years, but it could also go on forever.

## Appendix

<sup>1</sup>: My workflows are faster by not hardcoding any secrets. It makes it easier to re-use functions and rotate my expired API keys.


