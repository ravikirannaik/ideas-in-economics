---
title: "Module 2: Incentives and Human Behavior"
description: "Game theory, Nash equilibrium, strategic interaction, information asymmetry, and behavioral biases that shape economic decisions."
---

# Module 2: Incentives and Human Behavior

<span class="film-tag">:movie_camera: A Beautiful Mind (2001)</span> &nbsp; <span class="nobel-tag">:medal: John Nash</span>

---

## Overview

In Module 1, you learned that scarcity forces choices and every choice has a cost. But there was an unstated assumption lurking in that analysis: your choices affected only you. In reality, most of the decisions that matter in economics depend on what other people do. Should you study for the group project if your teammate might free-ride? Should a firm cut prices if its rival might match the cut? Should a country reduce carbon emissions if others refuse to follow? Should you bid high in an auction if doing so only invites others to bid higher still?

This is the world of **strategic interaction**, and it changes everything. When your best choice depends on someone else's choice --- and their best choice depends on yours --- you cannot simply weigh costs and benefits in isolation. You need a framework for thinking about interdependence. That framework is **game theory**, and its most important concept is the **Nash equilibrium**, named after the mathematician John Nash, whose life story is dramatized in this module's film, *A Beautiful Mind*.

This module takes you from the clean logic of individual optimization into the messy, fascinating territory where incentives collide. You will learn why rational individuals sometimes produce collectively irrational outcomes (the prisoner's dilemma), why markets can fail when one side knows more than the other (information asymmetry), and why human beings are not quite the coolly rational calculators that classical game theory assumes (behavioral biases). Along the way, we will see these ideas play out in settings as varied as IPL auctions, auto-rickshaw bargaining, nuclear deterrence, and India's telecom spectrum scandals.

---

## Key Concepts

1. [**Game Theory**](../../glossary.md#game-theory) --- the study of strategic decision-making where outcomes depend on the actions of multiple players
2. [**Nash Equilibrium**](../../glossary.md#nash-equilibrium) --- a stable outcome where no player can improve by unilaterally changing strategy
3. [**Dominant Strategy**](../../glossary.md#dominant-strategy) --- a strategy that is best regardless of what others do
4. [**Prisoner's Dilemma**](../../glossary.md#prisoners-dilemma) --- a game where individual rationality leads to collective irrationality
5. [**Cooperation**](../../glossary.md#cooperation) --- players working together for mutual benefit, often against individual incentives
6. [**Competition**](../../glossary.md#competition) --- rivalry among players seeking to maximize their own payoffs
7. [**Strategic Interaction**](../../glossary.md#strategic-interaction) --- situations where each player's outcome depends on the choices of others
8. [**Moral Hazard**](../../glossary.md#moral-hazard) --- when one party takes excessive risks because another party bears the cost
9. [**Adverse Selection**](../../glossary.md#adverse-selection) --- when asymmetric information causes the "wrong" types to dominate a market
10. [**Institutions**](../../glossary.md#institutions) --- the rules of the game that structure human interaction
11. [**Property Rights**](../../glossary.md#property-rights) --- legally enforced claims over assets that enable exchange and investment
12. [**Information Asymmetry**](../../glossary.md#information-asymmetry) --- when one party in a transaction knows more than the other
13. [**Heuristics**](../../glossary.md#heuristics) --- mental shortcuts people use to simplify complex decisions
14. [**Loss Aversion**](../../glossary.md#loss-aversion) --- the tendency to feel losses more intensely than equivalent gains
15. [**Bounded Rationality**](../../glossary.md#bounded-rationality) --- real people have limited information, time, and cognitive capacity for decision-making

---

## Game Theory: Thinking Strategically

Imagine you are at a traffic intersection in India with no signal and no traffic police. You want to go straight; the auto-rickshaw coming from your right also wants to go straight. If you both accelerate, you crash. If you both wait, traffic backs up and nobody moves. If one goes and the other waits, things work out --- but who goes first? Your best move depends entirely on what the other driver does.

This everyday scenario is a **game** in the economist's sense. A game has three ingredients: **players** (you and the rickshaw driver), **strategies** (go or wait), and **payoffs** (getting through safely, crashing, or being stuck). **Game theory** is the mathematical framework for analyzing such situations, and it was revolutionized in the 1950s by John Nash and his contemporaries at Princeton.

Game theory applies whenever your outcome depends on someone else's decision. This is not a niche situation --- it is the default condition of economic life. Firms set prices knowing their competitors will respond. Workers negotiate wages knowing the employer has alternatives. Countries set trade policies knowing that other nations will retaliate or reciprocate. Even within a household, the division of chores is a strategic interaction.

!!! example "Indian Context"
    The **IPL player auction** is game theory in action. Each franchise has a budget (the purse), a set of positions to fill, and imperfect information about other teams' strategies. Bidding too early reveals your priorities; bidding too late risks losing your target. Teams must anticipate rival bids, manage their remaining budget across future rounds, and decide when to drive up a price to exhaust a competitor's purse --- even for a player they do not want. The 2024 mega-auction, where franchises spent over Rs 550 crore collectively, was a textbook multi-player sequential game with incomplete information.

---

## Nash Equilibrium: Where Nobody Wants to Move

The central concept in game theory is the **Nash equilibrium**, and the intuition is surprisingly simple. An outcome is a Nash equilibrium if no player can do better by unilaterally changing their strategy, *given what everyone else is doing*. It is not necessarily the best outcome for anyone --- it is simply the outcome from which nobody has a reason to deviate on their own.

Consider a simple example. Two chai stalls set up on a long beach, and beachgoers buy from whichever stall is closer. Where should each stall locate? If one is at the quarter-mark and the other at the three-quarter-mark, they split customers evenly and everyone walks a short distance. But the stall at the quarter-mark can capture more customers by moving toward the center. The other stall responds by also moving center. The Nash equilibrium? Both stalls cluster at the exact midpoint of the beach. Neither can gain by moving. This is not ideal for beachgoers (who now walk farther), but it is stable --- neither stall wants to deviate.

This "beach stall" model, known as Hotelling's model of spatial competition, explains a striking real-world pattern: why competing businesses cluster together. Think of the row of phone repair shops near any Indian college, or the cluster of dhabas at highway junctions. Individually, they might prefer to be the only shop in their area. But the logic of strategic interaction drives them together.

!!! tip "Key Insight"
    A Nash equilibrium is stable, not optimal. Players end up there not because it is the best possible outcome, but because no one can improve their own situation by changing strategy alone. Understanding this distinction is essential for seeing why rational individual choices can produce collectively suboptimal results.

---

## The Prisoner's Dilemma: When Rationality Backfires

The most famous game in economics is the **prisoner's dilemma**, and it reveals a troubling paradox at the heart of strategic interaction.

Two suspects are arrested and placed in separate rooms. Each can either **cooperate** (stay silent) or **defect** (betray the other). If both stay silent, they each get a light sentence (1 year). If both betray, they each get a moderate sentence (5 years). But if one betrays while the other stays silent, the betrayer goes free and the silent one gets 10 years.

What should you do? Regardless of what your partner does, betraying is better *for you*. If they stay silent, betraying gets you freedom instead of 1 year. If they betray, betraying gets you 5 years instead of 10. Betrayal is a **dominant strategy** --- it is best no matter what the other player does. Since both players reason this way, both betray. The Nash equilibrium is mutual betrayal (5 years each), even though mutual cooperation (1 year each) would be better for both.

This is the paradox: individually rational behavior produces a collectively irrational outcome. The prisoner's dilemma is not just an abstract puzzle. It is the deep structure underlying some of the most important problems in economics and public life.

**Climate change** is a prisoner's dilemma. Every country benefits from others reducing emissions, but each country individually prefers to keep polluting (it is cheaper). The Nash equilibrium is too little emissions reduction, even though everyone would be better off with collective action. **Price wars** among firms follow the same logic: each firm undercuts to gain market share, and the equilibrium is lower profits for all. **Arms races** between nations, the overexploitation of common resources, and even the failure of students to contribute to group projects --- all are prisoner's dilemmas in disguise.

!!! example "Indian Context"
    The groundwater crisis in Punjab and Haryana is a prisoner's dilemma writ large. Each farmer has an incentive to pump as much groundwater as possible --- if they conserve, their neighbors will simply pump more, and the water saved is lost anyway. The dominant strategy is to pump aggressively. The Nash equilibrium is aquifer depletion. The water table in Punjab has fallen by over 10 meters in two decades, even though every farmer would benefit from collective restraint. Solving this requires changing the game itself --- through regulation, pricing, or community institutions that make cooperation enforceable.

---

## Cooperation vs. Competition: Escaping the Dilemma

If the prisoner's dilemma is the problem, what is the solution? Economists have identified several mechanisms that can shift outcomes from mutual defection to mutual cooperation.

**Repeated interaction.** When people interact repeatedly, the future casts a shadow over the present. If you betray me today, I can punish you tomorrow by refusing to cooperate. The threat of future retaliation makes cooperation sustainable. This is why long-term business relationships, village communities with stable membership, and nations engaged in ongoing trade tend to cooperate more than one-shot interactions predict. Robert Axelrod's famous 1984 computer tournament found that the simplest strategy --- "tit for tat" (cooperate first, then mirror whatever the other player did) --- consistently outperformed more complex strategies.

**Institutions and enforcement.** When voluntary cooperation is fragile, institutions can change the rules of the game. **Property rights** give people a stake in the future, making cooperation more attractive. **Contracts** backed by legal enforcement raise the cost of defection. **Regulations** can mandate cooperative behavior (emissions caps, fishing quotas, minimum safety standards). In the prisoner's dilemma framework, good institutions change the payoff matrix so that cooperation becomes the dominant strategy.

**Social norms and reputation.** In closely knit communities, reputation serves as an enforcement mechanism. Indian *jati*-based business networks historically operated on trust and reputation --- defaulting on a deal meant exclusion from future trade within the community. Similarly, online platforms like Amazon and Zomato use rating systems to make reputation visible, discouraging the "hit and run" behavior that plagues one-shot transactions.

**Communication.** Simply allowing players to talk can sometimes resolve the dilemma. If the two prisoners could communicate and make a binding promise, they would both stay silent. In real markets, this is why industry associations, trade bodies, and international summits exist --- they provide forums for players to coordinate on cooperative outcomes (though when firms coordinate on prices, we call it collusion and it harms consumers).

---

## Information Asymmetry: When One Side Knows More

Many of the most important market failures arise not from strategic interaction among equals, but from **information asymmetry** --- situations where one party in a transaction knows something the other does not.

### Adverse Selection: The Market for Lemons

In 1970, economist George Akerlof published a landmark paper asking: why do used cars sell at such steep discounts? His answer was that the seller knows the car's true quality, but the buyer does not. Since buyers cannot distinguish good cars from bad ones ("lemons"), they offer a price that reflects the *average* quality. But this average price is too low for sellers of good cars, who withdraw from the market. With good cars gone, the average quality falls, the price falls further, and the process continues until only lemons remain. This is **adverse selection** --- the asymmetry of information drives the good products out and the bad products in.

Adverse selection is everywhere. In health insurance, people who know they are sick are more likely to buy coverage, driving up premiums for healthy people. In credit markets, borrowers who know they are unlikely to repay are the most eager to take out loans. In the labour market, employers cannot perfectly observe a candidate's ability, so they use signals like degrees, certifications, and work experience as proxies --- a phenomenon Michael Spence formalized as "signaling."

!!! example "Indian Context"
    India's second-hand car market illustrates adverse selection vividly. Companies like CarDekho, Spinny, and Cars24 have built entire business models around solving the lemon problem. They offer independent inspections, quality certifications, and return guarantees --- all mechanisms to reduce the information gap between seller and buyer. Before these platforms emerged, the used car market in India was plagued by mistrust, with buyers demanding steep discounts and sellers of good cars preferring to sell through personal networks rather than face the "lemon discount" of the open market.

### Moral Hazard: Hidden Actions After the Deal

While adverse selection is about hidden *information* before a transaction, **moral hazard** is about hidden *actions* after one. Once you have fire insurance, you might be less careful about fire safety --- the insurer bears the cost of a fire, not you. Once a bank knows it will be bailed out if it fails ("too big to fail"), it takes larger risks. Once an employee is hired with a fixed salary, they might shirk --- the effort is costly to them, but the employer cannot perfectly monitor it.

Moral hazard is the economic reason why insurance policies include deductibles (you pay the first Rs 5,000 of a claim, so you still have an incentive to be careful), why employment contracts include performance bonuses (tying pay to output), and why shareholders demand oversight of managers (who might pursue personal interests rather than maximizing firm value).

!!! example "Indian Context"
    The **2G spectrum scandal** (2008-2012) is a case study in both information asymmetry and moral hazard. The government allocated valuable telecom spectrum to companies at below-market prices through an opaque first-come, first-served process rather than a transparent auction. The companies had better information about the spectrum's true market value than the allocation process revealed. Meanwhile, the politicians and bureaucrats who designed the process faced a moral hazard: they benefited personally from relationships with the companies receiving the cheap spectrum, while the cost --- estimated by the Comptroller and Auditor General at up to Rs 1.76 lakh crore in lost revenue --- was borne by the public. The Supreme Court's 2012 cancellation of 122 licenses and the subsequent shift to auction-based allocation was an institutional reform designed to address both problems simultaneously.

---

## Behavioral Biases: The Limits of Strategic Rationality

Game theory in its classical form assumes that players are perfectly rational: they know the rules, they can calculate the optimal strategy, and they execute it without error. John Nash's equilibrium concept rests on this assumption. But as we saw in Module 1 with Richard Thaler's work, real human beings are not perfectly rational. They use shortcuts, they are swayed by emotions, and they make systematic errors. These deviations matter enormously for understanding how strategic interactions actually play out.

### Heuristics: Useful Shortcuts, Dangerous Shortcuts

**Heuristics** are mental rules of thumb that help us make quick decisions without full analysis. When you choose a restaurant based on the length of the queue outside (rather than reading reviews of every option), you are using a heuristic. When a cricket captain decides to bowl first on a cloudy morning because "that's what you do," they are using a heuristic. These shortcuts are often sensible --- they save time and work well enough in familiar situations.

But heuristics can lead to systematic errors. The **availability heuristic** makes us overestimate the probability of events that come easily to mind. After a plane crash makes headlines, people fear flying even though driving is statistically far more dangerous. After a stock market crash, investors avoid equities for years even when valuations are attractive. The **anchoring heuristic** makes us rely too heavily on the first piece of information we encounter. If a shopkeeper in Colaba quotes Rs 2,000 for a scarf, your counter-offer of Rs 800 is still anchored to the initial price --- which may have no relationship to the scarf's actual value.

### Loss Aversion: Losses Loom Larger Than Gains

**Loss aversion** --- the finding that losses are psychologically about twice as painful as equivalent gains are pleasurable --- has profound implications for strategic behavior. A firm facing losses will take bigger gambles to avoid them than it would to achieve equivalent gains. A negotiator who frames a proposal in terms of what the other side will *lose* by rejecting it is more persuasive than one who frames the same proposal in terms of what they will *gain* by accepting.

In game theory terms, loss aversion means that the payoff matrix people *perceive* is different from the one economists *calculate*. A player facing a potential loss of Rs 1,000 treats it as psychologically equivalent to missing out on a gain of Rs 2,000. This asymmetry can shift Nash equilibria in unexpected directions and helps explain why people cooperate less than theory predicts in some situations (they fear being the "sucker" who cooperates while others defect) and cooperate more in others (they fear the loss of a valuable relationship).

### Bounded Rationality: Nobody Calculates the Nash Equilibrium

Herbert Simon coined the term **bounded rationality** to describe the reality that human cognitive capacity is limited. In a complex game with many players and many possible strategies, nobody literally calculates the Nash equilibrium and plays it. Instead, people use experience, intuition, and simplified models of the other players' behavior. They "satisfice" --- choose an option that is good enough --- rather than optimize.

This is not a failure of intelligence. It is a rational response to the costs of information and computation. The auto-rickshaw driver who quotes you Rs 200 for a 5-kilometer ride is not solving a bargaining game with full information about your willingness to pay, the outside temperature, the time of day, and the availability of other transport. They are using a rough heuristic based on distance, time, and experience. You, in turn, are not calculating your exact reservation price. You are comparing the quote to your vague sense of what is "reasonable."

!!! example "Indian Context"
    **Auto-rickshaw bargaining** in Indian cities without meters is a fascinating case of strategic interaction under bounded rationality. The driver quotes a high price. The passenger counters low. Both are using heuristics informed by experience, social cues, and reference prices. The outcome depends on context: a passenger carrying luggage signals urgency (and willingness to pay more); an empty street signals the driver has few alternatives. Neither party is optimizing in the textbook sense, but the interaction has a predictable structure that game theory illuminates even when its rationality assumptions are not perfectly met.

---

## Connecting to the Film

!!! film "Scene Connection: A Beautiful Mind (2001)"
    The film's most iconic economics scene takes place in a Princeton bar, where Nash has his flash of insight about equilibrium. Watching his friends compete for the attention of the same woman, he realizes that if everyone pursues the individually "best" option, everyone loses. The scene is a simplified illustration of a Nash equilibrium: the stable outcome is not the one where everyone competes for the top prize, but the one where each player adjusts their strategy in light of what others are doing. The film brings to life the key ideas of this module --- strategic interaction, the tension between cooperation and competition, and the power of thinking about other people's decisions before making your own.

    [:octicons-arrow-right-24: Read the full film analysis](film-analysis.md)

---

## Connecting to the Nobel Laureate

!!! nobel "Nobel Connection: John Nash (1994)"
    John Nash's Nobel Prize recognized his proof that every finite game has at least one equilibrium --- a result that transformed economics from a discipline focused on individual optimization into one that could analyze strategic interdependence. Before Nash, economists could say what a single rational person would do. After Nash, they could say what a group of rational people would do *to each other*. His equilibrium concept is now the default analytical tool in industrial organization, international trade, auction theory, political science, and evolutionary biology. The tragedy and triumph of his personal life --- decades lost to schizophrenia, followed by recovery and the Nobel --- makes his story as compelling as his mathematics.

    [:octicons-arrow-right-24: Read the Nobel Focus](nobel-focus.md)

---

## Interactive Explorations

Try these browser-based simulations to see the module's concepts in action:

| Simulation | What to Try | Link |
|-----------|-------------|------|
| **Demand Curve Explorer** | Shift demand and supply to see how equilibrium changes in competitive markets | [:material-open-in-new: Open](https://dmccreary.github.io/economics-course/sims/demand-curve-explorer/) |
| **Marginal Utility Meter** | See how satisfaction changes as consumption increases --- the foundation of rational choice | [:material-open-in-new: Open](https://dmccreary.github.io/economics-course/sims/marginal-utility-meter/) |
| **Budget Constraint Explorer** | Move along the budget line to see trade-offs between goods --- the individual's strategic choice set | [:material-open-in-new: Open](https://dmccreary.github.io/economics-course/sims/budget-constraint-explorer/) |
| **Elasticity Calculator** | Test how sensitive buyers and sellers are to price changes --- key for pricing strategy | [:material-open-in-new: Open](https://dmccreary.github.io/economics-course/sims/elasticity-calculator/) |
| **Diminishing Marginal Benefit** | Watch how the benefit of each additional unit declines --- the logic behind "enough is enough" | [:material-open-in-new: Open](https://dmccreary.github.io/economics-course/sims/marginal-benefit-pizza/) |

*Simulations from [Introduction to Economics](https://dmccreary.github.io/economics-course/) by Dan McCreary (CC BY-NC-SA 4.0)*

---

## Key Takeaways

1. **Game theory** analyzes situations where your best choice depends on what others do --- the default condition of economic life, not a special case.
2. A **Nash equilibrium** is an outcome from which no player can improve by changing strategy alone --- it is stable, but not necessarily optimal.
3. A **dominant strategy** is best regardless of what others do --- when one exists, the analysis is straightforward; the trouble is that it often leads to bad collective outcomes.
4. The **prisoner's dilemma** shows that individually rational choices can produce collectively irrational results --- it is the deep structure behind climate change, arms races, and resource overuse.
5. **Cooperation** can be sustained through repeated interaction, institutions, reputation, and communication --- escaping the prisoner's dilemma requires changing the game.
6. **Information asymmetry** causes two distinct market failures: **adverse selection** (hidden information drives out good products) and **moral hazard** (hidden actions after a deal encourage risk-taking).
7. **Institutions** and **property rights** are the rules that structure strategic interactions --- changing the rules changes the equilibrium.
8. **Heuristics** are mental shortcuts that are often useful but can produce systematic errors in strategic situations.
9. **Loss aversion** means people are more motivated to avoid losses than to achieve gains, distorting strategic behavior away from textbook predictions.
10. **Bounded rationality** reminds us that real people satisfice rather than optimize --- Nash equilibrium is a benchmark for understanding outcomes, not a description of how people actually think.

---

## Think Like an Economist

!!! question "Reflection Prompts"
    1. Think of a situation this week where your best decision depended on what someone else did. How did you handle the strategic interdependence? Did you try to predict their behavior, or did you just act and hope for the best?
    2. India's telecom companies regularly engage in price wars, each slashing rates to attract subscribers. Use the prisoner's dilemma framework to explain why this happens even though it reduces profits for all firms. What would it take to sustain higher prices (and is that desirable for consumers)?
    3. You are buying a second-hand motorcycle on OLX. The seller knows the bike's history; you do not. What information asymmetry problems might arise, and what strategies could you use to protect yourself?

---

## Next Steps

You now understand that strategic interaction is the norm in economic life, and that the outcome of your choices depends on the choices of others. Nash equilibrium gives us a powerful tool for predicting these outcomes, but the prisoner's dilemma warns us that stable outcomes are not always good outcomes. In Module 3, we move from individual and strategic behavior to the grand coordination mechanism of economics: **markets, trade, and the world of work** --- where the forces of supply and demand bring millions of individual strategic choices into a single, evolving system.

---

*Test yourself: [:pencil: Take the Module 2 Quiz](quiz.md) | Explore further: [:books: Module 2 Resources](resources.md)*
