This is an older version for sharing with the general public ***]
    Program uses yFinance, other libraries, and general financial calculations
    to report on the Probability of Profit (PoP) from 0 - 100%. Theoretically,
    if the PoP is high enough then profit is "assured." Assurance is based on
    statistical models and past performance (which is never a true indicator
    of future performance lol). Still, this exercise is useful to help a
    human identify where they might want to "hunt" for option trades.

  The basis of the statistical model is two-fold:
    1. Monte Carlo simulations,
    2. Black-Scholes model

  Variants of Monte Carlo simulations are used to price options, so it
    bodes well to use or prefer that model. I've included Black Scholes
    because it's recommended by the chatbots (but what do they know, right?)

  In any resolve, this applies solely to American options.

  Lastly, I completed outputting technical analysis
    (e.g., RSI, Bollinger Bands, etc.) on the underlying stock to further
    bolster analysis and help traders "hunt" for options.

  Special Note: Every brokerage house already provides this functionality
    in some form. Why then did I do this?
    I wanted to
        1. Return to coding -- being more technical is always positive
        2. Get my hands dirty / learn -- experience developer life up close
        3. Feel empowered by building my own customized and curated
              analysis - no brokerage house breaks down the ETF or Index
              holdings and lets you perform PoP analysis on them in 1 click.
        Yeah, if you select QQQ- you can either
            a/ Analyze the Nasdaq 100 (QQQ) options or
            b/ Analyze all 100 holdings within the Nasdaq 100 for potential
                  option trades. Wow!

every library that needs to be installed is checked by the program and 
automatically installed. HOWEVER, the codebase was first in Google Colab;
THEREFORE, the command install lines are !pip install -q <library>. The
exclamation mark would need to be removed to run this codebase. 
