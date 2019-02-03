---
title: "Software Collaboration"
date: 2019-01-26T11:39:36-08:00
draft: true
---

# Software Collaboration

Modern distributed software development marks the pinacle of text-based collaboration.
A global web of internet connected humans, of varying geopolitical and
educational background, working for different companies or none at all,
composing tapestries of textual repositories that give rise to our entire
digital society. 

The essential feature of software development is *distributed version control*, or, 
the "management of changes across agents".
This is an apt description of what societies, too, are collectively tasked with doing,
and probably has a lot to do with why software is eating the world.

## Git 

I don't know what software was like before git,
but it was surely nothing like it is now.
Apparently there was version control, but it wasn't distributed,
so I couldn't have my own branch - everything had to be merged to be committed.
Unfathomable! If the printing press transformed book publishing,
ushering in the Renaisance, Enlightenment, and the modern word, 
then Git seems to be doing the same for software publishing. 

The wild thing about git is it could do the same for so much more,
like legal contracts, accounting, and the many other aspects of managing
organizations. I'm hoping companies like [Rally]() can help further this cause.

Git provides integrity over changes ("commits") 
and facilitates many parallel worlds of development paths ("branches").
These primitives form a foundation for robust collaboration. 
They allow sequences of changes to be developed in parallel and to be
efficiently combined as they mature.

But git has some serious deficiencies.
For a developer raised in a culture of "don't trust, verify", 
git is so broken it hurts.


### Integrity

Putting aside that git uses a broken hash function (!), 
rebasing and cherry-picking annihilate the security model;
they provide no guarantee that the re-applied changes are the same.
Merging, too, is not without issue, as merge conflicts are resolved 
by a completely unaccountable process.
And this kind of behaviour is pervasive in professional software development.

It seems, then, that commits as is are an insufficient abstraction and we need
something that better differentiates actual "changes to the code" from "changes to the history".
That would allow us to verify that code was not changed in unexpected ways.

#


it appears at a different point in the history. , for instance, that a rebase or cherry-pick contains exactly the
code we expected.




This suggests a couple things.
One, rebase/cherry-pick should operations should 


Sure, rebasing and cherry-picking are convenient, nay,
critical to efficient development. 

But oh, the convenience! Surely, these commands are critical
to efficient development. But then they need to 


Rebasing is acceptable as a lone developer activity.
As soon as someone else has seen the code, rebasing n




Though it purports to provide integrity, 
it readily compromises it via rebases and cherry-picks.
And while it is outstanding for collaboration on a single repository,
it fails miserably in the multi-repo setting, encouraging abominations like
monorepos.



The fact that contracts, for instance, are still 

; the most frustrating being legal contract. 
If I lived in Silicon Valley, I'd sure be embarassed the lawyers
were still using Microsoft Word ;).


I can hardly stand that Git hasn't infected every other textual
form I engage in - contracts, accounting, emails, publishing, social media.


But because git is a local, distributed tool, it doesn't enforce



Notably, however, Git omits two critical elements of software development:
- Issue tracking and code review
- 
- What's the latest release?




On top of this foundation sits 

## Github

Github built a social media platform out of git's primitives, with no ads.
If only our other social media platforms could be so beneficially productive.




; they allow
independent contributors to propose sequences of changes to be combined 

Commits allow me to 


,,,


## Git Sucks

k

Git gives us 


So sounds like git give us back our individuality in what until then
been a highly centralized and fra








But git 
But I imagine it



Version control systems guarantee the integrity of changes, in the form of
commits and their hashes, but they can also give us authentication, by requiring
commits be signed.

Version control systems give us integrity and authentication - 
we have cryptographic digests of changes in the form of commit hashes,
and kk

I don't know what software development was like before Git. 



Strangers across the internet, composing a tapestry of repositories,


