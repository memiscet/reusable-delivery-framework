# Start here

You do not need to write code to use this framework. You need to explain what you want, read what the assistant proposes, and decide whether the result solves the problem.

Imagine asking someone to organize a community event. “Make it good” is difficult to act on. “Create a welcome sheet that tells guests where to arrive, whom to ask for help, and what to do if the room changes” gives that person something concrete to make and check.

The framework helps you turn the first kind of request into the second.

## The seven steps

| Step | Plain question | What you get |
|---|---|---|
| Scope | What problem are we solving, and what will we leave out? | A short agreement about the project |
| Architecture | How will the parts fit together? | An outline of the approach, tools, and responsibilities |
| Experience | What will someone do, see, and need help with? | A description of the journey, including mistakes |
| Decomposition | What useful pieces can we finish separately? | A list of deliverables with checks |
| Planning | How will we complete one piece? | Tasks, files, risks, and a definition of finished |
| Creation | Can we make what the plan describes? | The actual work and a record of checks |
| Review | What evidence shows that it works? | A verdict and any changes needed |

For a paper guide, “architecture” can mean who supplies the information, where the master copy lives, and how updates reach volunteers. It does not have to mean software.

## A few words you will see

A **skill** is an instruction card for the assistant. An **artifact** is something produced along the way, usually a file. A **deliverable** is one useful result, such as a welcome guide or a working search feature.

An **acceptance criterion** is a promise you can check. It has three parts:

> Given a guest has an old printed guide, when the room has changed, then the guide directs them to the welcome desk instead of telling them to guess.

“Given” describes the situation. “When” describes what happens. “Then” describes the result you expect.

An **evaluation criterion** checks the assistant's work process or output quality. “Every deliverable includes a check for something going wrong” is an evaluation criterion. It is different from the particular promise about the guest.

**YAML** is a way to write labeled information in a text file. The assistant can write it for you. You can still read the labels, such as `title`, `given`, and `then`. A **schema** is a checklist a computer uses to check those labels and their values.

## Your role

Start by explaining the problem, intended users, constraints, and what success would look like. Review the proposed scope before investing in a solution. Ask for smaller pieces when a deliverable feels too large to judge. For each finished piece, look at evidence against the promises you agreed on.

You can use all seven steps for a new project. For an existing project, keep the documents you already trust and fill only the gaps. A tiny task may need only a short scope, one deliverable, and a brief plan. The framework does not require a large document at every step.

## What passing means

A file check can tell you that the plan mentions every acceptance criterion. It cannot tell you that the plan is sensible. A review marked `passed` should have evidence for every promise. If a check was not run, its result must say so.

You can use the framework manually by opening files and following the cards. If you want automatic file checks, ask a technical colleague to follow the [setup guide](technical-setup.md).

Continue with [Your first project](../tutorials/01-first-project.md).
