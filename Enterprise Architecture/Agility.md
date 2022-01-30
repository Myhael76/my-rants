# Agility is About Taking Decisions Frequently

- [Agility is About Taking Decisions Frequently](#agility-is-about-taking-decisions-frequently)
  - [My Definition](#my-definition)
  - [Detailed Dive](#detailed-dive)
    - ["Take Decisions Frequently"](#take-decisions-frequently)
    - ["Generate Relevant Options"](#generate-relevant-options)
    - ["Implement Decisions in Useful Time"](#implement-decisions-in-useful-time)
  - [Some Real World Cases](#some-real-world-cases)
  - [References](#references)

There is a lot of content out there on what agility means or how different contexts interprets the term. The "agility" term is definitely not new in software engineering or organizational management, however it is also abused in some situations and greatly underestimated in other.

My opinion is that applying on of agility methods such as SCRUM is sometimes mandatory, yet not done, with clearly recognizable consequences.

## My Definition

To me, **agility is a system's ability to generate or recognize relevant options, take decisions frequently over those options and implement the taken decisions in useful time**.

Obviously, this article purpose is to explore how the definition applies to systems encompassing decisional agents, such as companies, operational or project teams.

Besides diving into each one of these characteristics, I will also discuss some relevant use cases that are frequently presenting themselves in an employee's life.

## Detailed Dive

### "Take Decisions Frequently"

To me this is the number one definitory trait of agility. I personally like Martin Fowler's statement ["adaptive planning is an essential element of agile thinking"](https://martinfowler.com/bliki/WaterfallProcess.html)

Very often, when various workgroups talk about "agility" they fall into the trap of defining the agility as a capability of delivering frequently what they call "product increments". To me, this is a consequence of being agile, and one of the verification means of the fact, but not a definitory trait.

I've seen the above bias repeatedly applied by project groups defining the "Statement of Work" upfront where that SOW clearly contained a "specification" initial phase. They were still thinking to define everything upfront and then deliver pieces of what has been defined in a more frequent manner. Normally this comes from classical project management concepts, where "the scope" is something that is known upfront either in excruciating detail or assumed to generate the excruciating details in a perfectly deterministic manner with some plannable activities such as "detailed design".

If we look at SCRUM, decisions are taken every sprint planning, as the very first activity that is done in a sprint. On the other hand not every sprint finishes with a deployable end-product increment, but the sprint increment may consolidate in unfinished pieces contributed to various places, such as modules or documentation. Furthermore, a sprint review may conclude that a piece of work is not yet "done" therefore forcing a sliding or canceling decision over the next sprint planning.

I would personally take a step further and state that the "scope of work", "product backlog", or whatever artifact defines the entirety of the problem domain, is also an object of the frequent decision. Having a big upfront "product backlog" that is rigidly blocked as a "scope" against a "time-budget" to form the well known classical project triangle is usually leading to non-agile project execution. Taking decisions frequently rather leads towards operational organizations that are constrained differently.

These decisions thus, although taken between governed guardrails, achieve their real value when they can transcend an upfront described scope. To understand better this aspect I feel we need to bring the [Lehman's SPE-classfication](https://www.expressionsofchange.org/lehman-spe-classification/) on our analysis table with a further detailed dive, which deserves it's own [article](./LehmanSPE.md).

### "Generate Relevant Options"

Without options, no decisions are needed and the outcome of the system becomes deterministic. We need options to weigh when deciding. In order to be agile, an organization must fully recognize the decision process.

Options must be available for every decision session. Being agile also includes the idea that the decisions taken are not leading to [zugzwang](https://www.dictionary.com/e/word-of-the-day/zugzwang-2021-08-16/) or closed road situations.

A good example of the value deriving from the decision to preserve options is given in the [Options](https://medium.com/@kentbeck_7670/decisions-decisions-or-why-baskets-of-options-dominate-9ac63658b593). It is proven that having more options enable value increments. However, taking decisions frequently may also have a cost, and a "business case" of being agile or not arises.

Sometimes organizations are not recognizing the need for frequent decisions. Other organizations consider the cost of frequent decisions unacceptable and prefer the comfort of upfront immutable decisions.

### "Implement Decisions in Useful Time"

Taking decisions imply the organization will execute some course of action. The "agility" notion sphere thus also include a certain hastiness of this execution. A slow execution that blocks other decisions, produce the outcome when the beneficiaries already received better options or arrives after it's maximum allowed reaction time is not considered to be agile.

If we are to consider Gregor Hohpe's [example of the steering wheel as an agility instrument](https://architectelevator.com/transformation/agile-steering/), let's consider a car that gives the steering wheel as a decision options and the user decides to steer in order to follow the road. If the car itself takes minutes to transmit the decision to the steering wheels, the user will most likely find themselves off road at the first curve.

In SCRUM's case, this time limit is expressed in the fact the actions should be done in a sprint.


## Some Real World Cases

In the real world, taking decisions frequently is necessary. Decisions are needed both  I am certain that any medium experience employee may recognize some of the following situations:

|Situation|Meaning|
|-|-|
|"this is the SOW of the project, this is the allowed time and budget, and by the way, I am allergic to CRs. Agile or waterfall is implementer's preference"|A higher level manager takes a single decision upfront and expects the end result without the need of intermediary decisions. Steering is organized with the base constraints of budget and time and corrections are always directed to the plan, staffing or administrative changes, but avoid product changes. SOW changes are eventually possible with significant sacrifices. The legal aspects frequently come in the center of the discussions.|
|"this was not specified upfront therefore it is a change request"|We are not allowed, not able or this is not the time to take a decision in merit|
|"business users are bad at specifying what they want and this is why we discover things late"|A detailed decision on what to do to satisfy business user need is required, but usually in conflict with the project constraints. It is likely we are applying an S-Type program at a P or E Type problem|
|"documentation is not up to date"|Documentation reflects the decisions taken upfront at a certain moment in time, but other decisions have been taken during the implementation and those were not fully managed because the project plan does not allow for iterations, therefore the decisions became unofficial and were buried in the unwritten knowledge of the implementation team|
|We have "freeze periods"|The "freeze" is referring to specification normally, bug fixes for example are allowed. The organization is applying S-Type programs to the involved domain|


## References

- [Options](https://medium.com/@kentbeck_7670/decisions-decisions-or-why-baskets-of-options-dominate-9ac63658b593)
- [Lack of Discipline is Agile Failure Mode #1](https://architectelevator.com/transformation/agile-discipline/)
