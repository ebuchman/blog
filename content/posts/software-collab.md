---
title: "Software Collaboration"
date: 2019-01-26T11:39:36-08:00
draft: true
---

Modern distributed software development marks the pinacle of text-based collaboration.
A global web of internet connected humans, of varying geopolitical and
educational background, working for different companies or none at all,
composing tapestries of textual repositories that give rise to our entire
digital society. 

The essential feature of software development today is *distributed version control*, or, 
the "management of changes across agents".
This is an apt description of what societies, too, are collectively tasked with doing,
and probably has a lot to do with why software is eating the world.

## Git 

I don't know [what software was like before
Git](https://hackernoon.com/how-git-changed-the-history-of-software-version-control-5f2c0a0850df),
but it was surely nothing like it is now.
Apparently there was version control, but it wasn't distributed,
so I couldn't have my own branch - everything had to be merged to be committed.
Unfathomable! If the printing press transformed book publishing,
ushering in the Renaisance, Enlightenment, and the modern world, 
then Git seems to be doing the same for software publishing. 

The wild thing about Git is it could do the same for so much more,
like legal contracts, accounting, and the many other aspects of managing
organizations. I'm hoping companies like [Rally](https://rallynow.io/) can help further this cause.
If I die young, it will probably be out of frustration from not being able to
manage my companies the way I manage my software.

[Git](https://git-scm.com/) provides integrity over changes ("commits") 
and facilitates many parallel worlds of development paths ("branches").
These primitives form a foundation for robust collaboration. 
They allow sequences of changes to be developed in parallel and to be
efficiently combined as they mature.

However, as a local, distributed tool, Git doesn't define an authoritative
latest state of the codebase. It does not provide tools for enforcing authority 
or release workflows. It makes no accomodation for the actual consensus process under
which the software evolves.

These functionalities have so far been delegated instead to the likes of 
[Github](https://github.com).
Github, of course, is an enormous component of Git's success.
Using Git's primitives, Github built the world's most beneficially productive social media platform,
and they did it without any ads. Github is the environment for the consensus
process under which software managed by Git evolves. 

While marvelous, the current state of Git and Github has some serious deficiencies.
For a developer raised in a culture of ["don't trust, verify"](https://store.blockstream.com/product/dont-trust-verify-tshirt/), 
it's so broken it hurts.

### Integrity

Putting aside that Git uses a [broken hash function (!)](https://shattered.io/), 
rebasing and cherry-picking annihilate the security model;
they provide no guarantee that the re-applied changes are the same.
Merging, too, is not without issue, as merge conflicts are resolved 
by a completely unaccountable process.
And this kind of behaviour is pervasive in professional software development.

It seems, then, that commits are an insufficient abstraction and we need
something that better differentiates actual "changes to the code" from "changes to the history".
That would allow us to verify that code was not changed in unexpected ways.

Alternative version control systems seem to be exploring just these issues.
As they say about [Fossil](https://www.fossil-scm.org), the Git of
[SQLite](https://www.sqlite.org/index.html),
"Git records history according to the victors, whereas Fossil records history as
it actually happened." And [Pijul](https://pijul.org/), a new tool based on a sound
theory of patches, makes the actual change the primary primitive, rather than
the commit, addressing many of the issues with rebasing, cherry-picking, and merge
conflicts. I'm very much looking forward to experimenting with Pijul!

### Dependencies

Git is definitively a tool for managing single repos.
While it has a `submodule` command for vendoring external repos,
it seems, as they say, to have made a lot of people very angry and been widely regarded as
a bad move. When you need to develop multiple repositories in parallel, this becomes
a significant problem.

The trouble with maintaining a public facing repository for use as a library,
independent of a main repository containing an executable, is
that it takes a lot of work. It requires its own issue tracking and code review
process, project planning, and release management. It needs changelogs and versions. 
It requires you to update code in multiple places to get new versions.

Another problem is that Github doesn't let you atomically merge branches across
repositories at the same time. While a minor problem, if you seek purity and
correctness in your life, and you want your repos to work together on the latest master branch
(hardly an unreasonable ask), this may cause you serious brain damage. 
Try not to take it too seriously if you can.

Many folks have purported to solve these issues by using a
[*monorepo*](https://en.wikipedia.org/wiki/Monorepo) - just
throw all the code in a single repo and the problem is solved. 
As Churchill was overhead saying about the use of monorepos in the fight 
against the Nazis, it is "the worst form of version control, except for all the others".
Eventually, the size of the monorepo will grow to the point that Git becomes unable 
to efficiently manage it and you need bespoke tools. 
Apparently this is how it works at places like Facebook and Google, though it
remains uncertain which side such companies are on in the perenial fight against
Naziism. In any case, since Golang was developed by and for Google, this
partially explains why they punted on dependency management for so long.
With the developer hours wasted on dependency management in Golang to this date,
we probably could have solved very hard problems in computer science, 
[like Death and Taxes](https://twitter.com/oleganza/status/927678629391171584).

So what is one to do? Probably use the monorepo approach as much as is
reasonable - no more, no less. This means to break things out of the monorepo as
soon as you have the actual capacity and desire to maintain the independent
repository - its project planning, merge process, changelog, versioning, etc.
If you have the capacity to build bespoke version control tooling, you almost
certainly have the capacity to maintain independent repositories, but perhaps
you're still trying to defend yourself from the brain damange inherent in the
lack of atomic releases across said repos. Whatever you do, don't you dare 
underestimate the cost of maintenance of an independent repo. It's roughly on
the same order as maintaining a small zoo.

Perhaps new tools based on content addressable data will emerge to aid this process, and to better support atomic
multi-repository releases. Perhaps something built on [IPFS](https://ipfs.io/). I remain hopeful.

### Workflow 

So you thought you were pretty cool, developing software on your own in your
underwear in a basement for a while. Then suddenly you find yourself on a
*team*, and shit hits the fan. Does your basement even have a fan?

... releases, security, radicle

### Legal Contracts

## Conclusion


