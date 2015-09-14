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

This quote is interesting because although this was written 17 years ago, we can see this happening with languages being chosen for teaching 
introductory programming. For most of the late 2005-2010, Java was the main language that was used to teach programming. This can be seen from 
College board choosing to move from C++ to Java for the Computer Science AP class. Now that Java has had a lot added to it over the years, it
is the old, hard to enter language. Smaller languages like Python and Ruby have started to take the place as introductory languages 
mostly because of their simplicity. This should make us think about how additions, while great for existing users of the DSL, might harm 
acquiring new users. 

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

	There are many ways to define a well-designed language. We believe that language simplicity, understandability and the ability for users to add their 
own parts encompass a well-designed language. 

	I think it would be best to start by using examples from Steele. From a quote we used in question one, Steele explains "if the design of the Java 
programming language as it is now had been put forth three years ago, it would have failed — of that I am sure" [Steele, 1998]. 
So it seems like, at least intial, simplicity is a key to good language design. Pavlus states that "He said that their usability testing showed that simply finding natural-language replacements for some of the more abstruse syntax went a long way." [Pavlus, 2012] He agrees with Steele in that he argues that language with simpler syntax, or syntax that the user is more familiar with, allows for new users of the language to accomplish tasks in much less time. This also argues for both undestandability and simplicity. Bloch also agrees with understandability by saying that well written APIs should "read like prose." [Bloch, 2006] Steele also argues that a language shouldn't do more than it has to.He says that "what we need is more like a shopping mall, where there are not quite as many choices but most of the goods are well designed and sellers stand up and back what they sell." [Steele, 1998] So a language should allow for flexibility but not do to much for the user. 

We both agreed that badly designed languages boil down to being hard to understand and hard to implement thoughts from our head. This can be either understanding plain syntax or understanding how parts of the language work to having language design that requires work arounds to do tasks that our mind would find simple. 

Pavlus quoted from a researcher that "Perl users were unable to write programs more accurately than those using a language designed by chance." [Pavlus, 2012] This stemmed from, they said, hard to understand syntax. If it is hard for a user to understand the syntax, using that syntax to make difficult programs is going to be even harder. Since languages are designed to make writing programs easier, this is probably a symptom of bad-language design. Blach agrees by stating a requirement for a good API is "obey the principle of least astonishment." [Blach, 2006] By having the language do what the user thinks it should do with a specific call, less errors and rewriting will have to occur for the user to get to the right syntax. 



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

Pavlus is arguing that programming languages should be designed to be easier for the average person to understand and learn. While we agree with this general argument of the article, the actual specifics Pavlus uses to bolster his claim are not convincing. The commenters point out that Pavlus is emphasizing the difficulty of learning a language for those new to the language, but they argue that a programming language should be designed more with its users in mind, in that ease of use should be the concern, not ease of learning.

We mostly agree with the commenters. The language Pavlus seems to be after is a language for teaching programming, not one for actually programming. The reason that his "hieroglyphic" programming languages stick around is that they are useful. The commenters are right that there is a trade-off between a language being readable by the general public and how efficient and powerful a language is. We resent Pavlus for implying that such a trade-off need not be there, and that contributors to programming language design don't care enough to make their languages usable. Does he think that nobody has thought of this before?

However, we do not totally disagree with Pavlus. We actually agree with his general arguments, just not with how he defends them. We believe that it would be possible for languages to be more accessible to the general public. For example, Python has had great success with being a language designed with a guiding principle of "Readability counts," as well as "Beautiful is better than ugly" ([PEP 20 -- The Zen of Python][1]). It is not too hard to imagine a language that goes a bit farther than Python while still being very powerful and usable.

We also note that both Pavlus and the commenters are focusing too heavily on one set of users. Pavlus seems only to care about having as many people as possible understanding a program. This to us seems silly, it is a career for a reason: you wouldn't expect the whole public to easily become good lawyers. Maybe at some point in the future programming will become more commonplace, but we are not there yet. Likewise, the commenters are fully rejecting the idea that more people could learn programming, and that that would be a good thing. This is too narrow-minded; of course programming languages should be understandable. The question is how understandable they should be, but the commenters don't even seem interested in that discussion. We would guess that part of why they have these blinders on is because they are professionals, they know how their languages work, and they don't need anything to change for them. But we believe it is very possible that a change for more readability could happen without negatively affecting the programmers.


[1]: https://www.python.org/dev/peps/pep-0020/

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
