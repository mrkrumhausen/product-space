---
layout: default
title: Run Experiments
description: Use experiments to understand if something is a good idea (and learn from this understanding).
nav_order: 2
---

# Experiment your way to success
You should run experiments to assess the value of an idea. An idea often comes as a solution to a user’s pain/need.
{: .fs-6 .fw-300 }

## When to run

## Why


## The experimental approach
In the experimental approach, we try to run simple experiments as fast as possible in order to learn if something is a good idea. Here the focus is on testing / failing fast

*1 Idea > 2 Measure (experiment) > 3 Decision > 4 then Build*

When you have run the experiment and gained knowledge about an idea, it is time to make a decision based on evidence.

<!-- ## Focus on outcomes, not outputs
The way we measure performance should reflect the experimental approach: The focus of product development team should be on the outcome and not deliveries. If the team delivers something on time, budget and quality, but nobody wants to use it, we have wasted time and money.

A development team’s responsibility is not only to deliver code, but to run experiments to understand if something is a good idea; hereby identifying new opportunities and ultimately, ship a product that satisfy their customers’s needs. -->


## How to experiment
Think like a scientist. Treat each experiment as an opportunity to learn what is and is not working. Designing a good experiment is key. It should have:

1. A clear, falsifiable hypothesis
1. An obvious next action
1. Strict risk containment
1. A tie between what is measured and at least one leap of faith assumption

###  Experimentation brief
A concise document that paints a clear picture of the problem space and what we’re trying to accomplish.

```yaml

# 1. The Business Objective
Describe the business goal / problem / need / opportunity you’re looking to solve.
- **Who are we solving for?** Who will benefit from this and how?
- **KPIs**. How will we know if this experiment is successful? Define "Success": What are the key metrics that we expect this to improve? (e.g. songs streamed, number of downloads, etc.)
- Why is this business objective important? This is where you tie your project to the larger context of the company.

# 2. Hypothesis
List your hypothesis and make it measurable, e.g. *adding a buy button next to the product will increase conversion by 20%*.

**Pro tip**: Test multiple different versions to find the version by focusing on breadth rather than depth.

# 3. Experiment design
The description of the solution/implementation. How will you run the experiment?
- What's in / out of scope?

**Considerations**:
- Who needs to be involved?
- What problems do we need to solve? Identify unknowns, areas of risk, and known challenges that need to be resolved before development can begin.
- What is already built? A short description of existing and related features that give context to the new project.
- What future considerations need to be accounted for? Are there future features or business goals that will build on top of this feature? Goal is to not design ourselves into a corner now if we know about something in the future.

**Pro tip**: The experiment should be fast and inexpensive to run, e.g. "*I’ll pick up my phone and call three of them right now to see what they think about it.*", "*I'll add a fake door to see if people are interested in the new feature*"

**Pro tip**: The [Sample Size Calculator](http://www.evanmiller.org/ab-testing/sample-size.html) gives you a way to determine what size audience you need for your tests.

# 4. Results
List the key findings.
```


## Different types of experiments
Running online experiments is very cheap, so running them early in a discovery process is an advantage. Run a kill experiment as fast as possible to validate your idea without getting too attached to it.

### Will users buy it?
This experiment focuses on one thing only: *Will users buy it?*

To know if customers will buy it (use it), the experiment must follow certain principles to work:

1. Users have to believe the product/feature exists (users cannot know they are part of an experiment).
1. Users have to commit **to buying** the product/feature (e.g., by giving their email or clicking a payment method).

Example: a simple website with minimal functionality, that mimics the full experience.

You can start with a simple proof-of-concept experiment (PoC). These types of experiments are allowed to be low fidelity; You don’t need polished a design, and it’s okay to have some friction in the user journey. The point is not to test a flashy feature or idea. The point is to see if users do what we expect them to (measuring behavior).

### Fake door
Build the door for the feature without actually building the feature and measure the interest. If enought users click (engage) then it's worth building the feature.

### A/B or split testing
The regular version of a product (called Control) is compared against a modified version (the B Variant or the Challenger) and checked for effects on a company's guiding metrics (or Overall Evaluation Criteria, OEC). Test with a small percentage of users, usually 1-5%

**Pro tip**: a couple of bigger tech companies have open sourced their internal systems for others to use. See Cloudera’s [Gertrude](https://github.com/cloudera/gertrude), Etsy’s [Feature](https://github.com/etsy/feature), and Facebook’s [PlanOut](http://facebook.github.io/planout/), for example.


## Concluding notes
Experimentation is typically run when teams have enough traffic to empirically and scientifically test whether a change will produce the intended effects with a cohort of real users. Teams using experimentation should ensure they have adequate levels of traffic, they understand the problem they are trying to solve and they have ensured the impact of their changes can and should be measured through an experiment.

## References
- [https://medium.com/the-experimental-approach/the-experimental-approach-e6a01a4b941e](https://medium.com/the-experimental-approach/the-experimental-approach-e6a01a4b941e)
- [https://productcoalition.com/six-templates-for-aspiring-product-managers-a568d3115cfe](https://productcoalition.com/six-templates-for-aspiring-product-managers-a568d3115cfe)

## Related plays
- [Minimum Viable Product](plays/mvp)
