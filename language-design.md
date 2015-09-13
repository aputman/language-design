_Fill in each this file with your responses, placing each response after its
corresponding question._

---

**Question**

Pick three quotes from the readings about language design. Good candidates 
are:

   + Something you agreed with / resonates with your own experience
   + Something you disagree with
   + Something that is interesting, a new idea or perspective you'd like to remember
   + Something you didn't understand

For each quote, describe what it was about the quote that led you pick it.

**Response**

Quote 1: "The broad computer science academic community has not paid a tremendous amount of attention to programming language usability" [Pavlus, 2012].
BEN

What is the author's and researcher proposed solution?
- if it so easy to pay attention to usability, why hasn't the perfect language been developed?
- question title?

What defines usability and how can you maximize usability for all different end users?
- While perl might be too hard for beginners, experience developers with the language can do quite a lot, which the perl community probably catered to

Quote 2: "Public APIs, like diamonds, are forever" [Bloch, 2006].
BEN

Different than what we are used to
- Need to start questioning backwards compatability with language updates

Experience with user vs developer time development needs
- Getting something out for the need of getting it out vs being ready to send it out. 

Quote 3: "If the design of the Java programming language as it is now had been put forth three years ago, it would have failed — of that I am sure" [Steele, 1998].
ALEX 

Relate to current day
- Written 17 years ago, Java being phased out as introductory language in favor of lighter alternatives
- People new to programming choose languages based on simplicity vs. research/need?

---

**Question**

How do the themes of _Growing a Language_ relate to the lab we did this week?

**Response**
BEN

Themes:
- Fluidity or languages extending thought vs conforming thought to the language. 
	- Language expansion as the thoughts for the domain expand. 

- In the lab we had a process that someone in the domain might want to achieve. 
- We then designed the language to best suit that process, basically extending it


---

**Question**

How would you know a well-designed language? What are the symptoms? How would
you know a poorly designed language? What are the symptoms?

**Response**
ALEX

Steele 
- WELL: must have tools to easily extend or grow the language and allow users to do the same
- POOR: no way for the community to give feedback or help, basically if plans are too strict

Why are Languages design better?
- WELL: easily understandable syntax, low barrier to entry
- POOR: reversed 

How to design a good API
- WELL: Make every aspect of the API well defined to the use-cases and known to the user. Reads like prose (quote)
- POOR: API doesn't do what user thinks it will do, allows user to do something that the API isn't intended for

---
 

In what way is an API a language? 

**Response**

ALEX 

Outside Reading: Fowler:


API reading:
- Good programs are modular, and intermodular boundaries define APIs. Good modules get reused.

as discussed in class:
- languages are instructions that are computed
- APIs are instruction that don't allow for addition logical sugar between them, has to be done in another language


---

**Question**

The comments on the Pavlus article seem to set up a conflict between
professional programmers and everyone else. What is the essence of this
conflict? Do you sympathize more with the substance of the article's arguments
or with the substance of the majority of the commenters' arguments? Do you
sympathize more with the tenor of the article or the tenor of the majority of
the commenters?

**Response**
BEN

While we agree with the argument of the article, the actual specifics to bolster his claim are not convincing.
As the commenters point out, he is only considering new users to a language vs experienced developers. 

Both the author and the commentors fail to consider the users that are not under the scope they are arguing for. 
There is definitely a middle ground that is being sought out but both groups fail to even attempt to find it. 

The comments also highlight a heavily perceived social difference between those who know how to code and those 
trying to learn. We do sympathize that this could be a problem in the persuit of finding the middle ground. 

---

**Question**

How do implementation choices (e.g., as an interpreter/compiler or as an
internal DSL) affect the user experience? Can or should we always hide our
implementation choices from users?

**Response**
BEN

Fowler Reading

last reading - last paragraph of 328
internal

external - 330

2.5.2


Easier to understand syntax in internal DSL but might be harder to destinguish what 
you are supposed to do. 

With a restricted syntax, it might be that its impossible to do anything but what
you are supposed to do.

Can't if its a syntax decision, its easier to hide if its just a semantics decision vs syntax decision

how to make API?
- keep implementation details away from users, overspecification is bad

---

**Question**

The Pavlus article mentions the researchers' comments that people preferred
"natural-language replacements for some of the more abstruse syntax". In other 
words, people found it easier to work with code that looks more like a human language (e.g.,
English). Consider the following quote by William R. Cook, one of the creators
of JavaScript:


> The experiment in designing a language that resembled natural languages (English
> and Japanese) was not successful. It was assumed that scripts should be
> presented in “natural language” so that average people could read and write
> them. … In the end the syntactic variations and flexibility did more to confuse
> programmers than to help them out. It is not clear whether it is easier for
> novice users to work with a scripting language that resembles natural language,
> with all its special cases and idiosyncrasies. The main problem is that
> AppleScript only appears to be a natural language: in fact, it is an artificial
> language, like any other programming language. … even small changes to the
> script may introduce subtle syntactic errors that baffle users. It is easy to
> read AppleScript, but quite hard to write it.
[[Cook 2007, page 1-20]](https://dl.acm.org/citation.cfm?doid=1238844.1238845)

Are these two experiences of natural languages at odds with one another? Would
you choose to include natural language in the design of a DSL? If so, how might
you do so? If not, why not?

**Response**
ALEX

No, Pavlus is basically talking about being introduced to programming and Cooke is talking
about the problems that arise when you try to do more complicated things. 

Depends on the user and on the domain. If the language of the domain is very defined and 
specific, then there wouldn't be must ambiguity in how people of that domain would interpret 
it.
- Instead of making a natural language language, just change operators or keywords to fit the language 
of that domain to make it more readable. 

If there is ambiguity we would not because if a line could be interepreted by a human in several different ways
and only in one way by a computer, not everyone will get what they expect. 

---

**Question**

Briefly describe how you split up the work for this assignment.

**Response**



---
