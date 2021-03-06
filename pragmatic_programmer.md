# [The Pragmatic Programmer](https://pragprog.com/titles/tpp20/the-pragmatic-programmer-20th-anniversary-edition/)

Overall fun, lightweight and easy to read. Lots of simple, pratical advice, but doesn't go too deep in any direction.

Mostly liked the way it puts "implicitly obvious" concepts (sort of unknown-knowns for most software developers I know) into clear short chapters.

## Quotes:
- Programming is about trying to make the future less painful.
- > Why didn't anyone ask the users?
- As a programmer, you are part listener, part advisor, part interpreter, and part dictator.
- [When something can't be done or goes wrong] provide options.  
Don't say it can't be done, explain what can be done to salvage the situation.
- When you find yourself saying "I don't know", be sure to follow it up with "—but I'll find out".
- **Don't leave "broken windows" (bad designs, wrong decisions, or poor code) unrepaired.**
- [On solving start up inertia]. Work out what you can reasonably ask for. Develop it well, show people. Wait for them to start asking you to build the functionality you originally wanted. People find it easier to join an ongoing success. Show them a glimpse of the future, and you'll get them to rally around.
- YAGNI:
  - Write software that's *good enough* - good enough for your users, for future maintainers, for your own peace of mind.
  - Users [should] be given an opportunity to participate in the process of deciding when what you've produced is good enough for their needs.
  - [Painting metaphor] Hard work becomes ruined if you don't know when to stop. If you add layer upon layer, detail over detail, the painting becomes lost in the paint.
- Continuous learning
  - Managing a knowledge portfolio is very similar to managing a financial portfolio.
  - Invest regularly, most important and simplest
    - Learn at least a new language every year.
    - Read books. (Mythical Man Month, Peopleware)
    - Take classes.
    - Participate in local user groups and meetups.
    - Stay current (read some news on current tech).
    
  - Diversify.
  - Balance portfolio between conservative and high-risk, high-reward investments. [[Reminds me of the barbell strategy](https://en.wikipedia.org/wiki/Barbell_strategy)]
  - Portfolio should be reviewed and rebalanced regularly.
- **"The meaning of your communication is the response you get".**
  - [Use this short chapter as guide when writing something, too long to copy here]
- ### Good design is easy to change.
- Essence of DRY: *Every piece of knowledge must have a single, unambiguous, authoritative representation within a system*.
    - If it's duplicated it will soon become inconsistent, fun analogy with Start Trek evil AIs being taken down by contradictory pieces of knowledge.
- Don't rely on properties of things you can't control.
- Tracer bullets: [**end to end**, minimal feature around which to build the system.]
  - Look for the important requirements, the ones that define the system. Look for areas where you have doubts, and where you see the biggest risks. Prioritize development so that those are the first areas to code.
- The palest ink is still better than the best memory.
- Which files get changed most often?
- If it took a long time to fix a bug, ask yourself why. [and how to make it easier next time]
- *Keep an engineering daybook* [Can use it for standup]
- **Tell, don't ask**: you shouldn't make decisions based on the internal state of an object and then update that object. [See examples]
- *An event represents the availability of information.* [Reminds me of bayesian updating]
- **Think of programs as being something that transforms inputs into outputs.**
- Don't live with broken windows (see above, but worth repeating).
- On TDD:
  - If you think about testing boundary conditions and how that will work *before* you start coding, you might find patterns in the logic that'll simplify the function. Think about the error conditions and structure code accordingly.
  - The only way to build software is incrementally. Build small pieces of end-to-end functionality, learning about the problem as you go. Apply this learning as you continue to flesh out the code, involve the customer at each step, have them guide the process.
  - "Test later" means "test never".
- The beginning of wisdom is to call things by their proper name.
- Programmers help people understand what they want. Help the client understand the consequences of their stated requirements.
- Requirements are not architecture. Requirements are not design, nor they are user interface. Requirements are *need*.
- Use a burn-up chart instead of a burn-down chart to keep track of feature creep. [[burn-down chart](https://en.wikipedia.org/wiki/Burn_down_chart)]
- Exercises:
  - Use the software you're writing, to try to get a good feel for the requirements.
  - Pick a non-computer-related problem and generate requirements for a non-computer solution.
- Categorize and prioritize constraints. (woodworking metaphor: cut biggest pieces first --> identify most restrictive constraints first, and fit the others within them)
- Delight your users
- How will you know that we've all been successful a month (or a year) after this project is done?

See also:
 https://blog.codinghorror.com/a-pragmatic-quick-reference/ (interesting that of all the suggested languages, only Objective C became "mainstream")
