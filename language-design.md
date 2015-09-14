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

Quote 1: "Why shouldn’t those 'interfaces' be as humanely designed as the ones we tap and swipe?" [Pavlus, 2012].

Here Pavlus asks why programming languages' interfaces are not as "humanely designed" as software's graphical interfaces are. This quote stood out to us because Pavlus is trying to make a point, but actually ends up asking a question that is very easy to answer! One answer is that in general, software (programming languages included) is designed towards its users. The software Pavlus is referring to is probably targeted at a much broader audience, so it needs to be easier. Also, we take issue with Pavlus implying that programming is comparable to tapping and swiping. Is Pavlus claiming that programming should be as easy as Angry Birds? I doubt that would be a productive language.

Quote 2: "Public APIs, like diamonds, are forever" [Bloch, 2006].

This is not a feeling that we are used to. I (Ben) have never written anything like this, anything that would be public-facing and would cause an outcry if changed. It is interesting to think how choices made at the outset could affect your language fifteen years later, possibly. In fact, every future time you change something, you'd have to ensure backwards compatibility. It really emphasizes how thoughtful one needs to be in designing a language or an API. It is in general much better to wait until you are ready than to send out a rushed product.

Quote 3: "If the design of the Java programming language as it is now had been put forth three years ago, it would have failed — of that I am sure" [Steele, 1998].

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

Steele states his main theme on page 5: "I should not design a small language, and I should not design a large one. I need to design a language that can grow. I need to plan ways in which it might grow — but I need, too, to leave some choices so that other persons can make those choices at a later time." His point is that programming languages should not try to implement everything, but rather should allow the users to implement anything. He goes on to say that languages can and should expand, but that this rate must be controlled. As an example, he claims that Java in its state three years after its creation would never have been accepted as a programming language; it had to have those three intervening years to grow.

This theme plays a part in our lab from last week. Our goal in the lab was to create an extension for Python that would allow users to easily manipulate sounds. There are two things to note here. One, Python does not already have what we are looking for (there are some libraries out there that do this, but they were not part of Python's original design). Two, we were able to with little effort implement the desired functionality in Python. This fits nicely into Steele's description of the size of a language: Python was not too big, because its original specification did not contain this; and Python was not too small, because it was rather easy to implement the desired functions with basic Python functionality. Here we must say that Steele does not say that languages have to remain small. Python has grown to include libraries that already do what we implemented, but this does not contradict Steele because Steele expects languages to grow, just not for all that growth to be part of the original design.

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

Pavlus quoted from a researcher that "Perl users were unable to write programs more accurately than those using a language designed by chance." [Pavlus, 2012] This stemmed from, they said, hard to understand syntax. If it is hard for a user to understand the syntax, using that syntax to make difficult programs is going to be even harder. Since languages are designed to make writing programs easier, this is probably a symptom of bad-language design. Bloch agrees by stating a requirement for a good API is "obey the principle of least astonishment." [Bloch, 2006] By having the language do what the user thinks it should do with a specific call, less errors and rewriting will have to occur for the user to get to the right syntax. 



---
 

In what way is an API a language? 

**Response**

ALEX 

Fowler states that the saying in old Bell labs was "library design is language design." [Fowler] As we discussed in class, languages could be defined as instructions that are computed. With that simple definition, an API is a specified set of instructions that we know can be computed but don't necessarily know how they are computed. The goal of a language is for us to be able to complete a task in a simpler way than we could without that language. Depending on the intended use of the API, that is what it can do. As we have discussed earlier, Poole talked about how Java was initially designed to be as concise as possible to fulfill all the needs of the user. Bloch said that "every facet of an API should be as small as possible, but no smaller." These agree in that both should be able to accomplish what the user would want to use the language or API for but not more, which would frustrate or confuse the user. 

Bloch states that APIs should "obey the principle of least astonishment." [Bloch, 2006] Just like languages, if a user expects the API to do something, the API should most likely do that thing. This follows languages in being designed how users are used to certain things being represented and used to certain operations existing. So like languages, APIs should revolve around how a user would expect to use it. 




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

However, we do not totally disagree with Pavlus. We actually agree with his general arguments, just not with how he defends them. We believe that it would be possible for languages to be more accessible to the general public. For example, Python has had great success with being a language designed with a guiding principle of "Readability counts," as well as  "Beautiful is better than ugly" ([PEP 20 -- The Zen of Python][1]). It is not too hard to imagine a language that goes a bit farther than Python while still being very powerful and  usable.

We also note that both Pavlus and the commenters are focusing too heavily on one set of users. Pavlus seems only to care about having as many people as possible understanding a program. This to us seems silly, it is a career for a reason: you wouldn't expect the whole public to easily become good lawyers. Maybe at some point in the future programming will become more commonplace, but we are not there yet. Likewise, the commenters are fully rejecting the idea that more people could learn programming, and that that would be a good thing. This is too narrow-minded; of course programming languages should be understandable. The question is how understandable they should be, but the commenters don't even seem interested in that discussion. We would guess that part of why they have these blinders on is because they are professionals, they know how their languages work, and they don't need anything to change for them. But we believe it is very possible that a change for more readability could happen without negatively affecting the programmers.


[1]: https://www.python.org/dev/peps/pep-0020/

---

**Question**

How do implementation choices (e.g., as an interpreter/compiler or as an
internal DSL) affect the user experience? Can or should we always hide our
implementation choices from users?

**Response**

The choice of implementation for a DSL strongly affects its userse. If we choose to implement an internal DSL, then users can have an easier time learning the language, because users may already be familiar with the host language. Even if they are not, the host language will have documentation, so it will likely be easier to pick up the DSL than if the DSL was a totally new language. On the other hand, if we implement our DSL as external, there is the advantage that we can choose syntax that makes sense to experts in our chosen domain. If those experts are our users, that will help them.


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

No, we don't believe that the two experients disagree with each other. Pavlus is not arguing for a "natural language" but more for a language that is easier to understand by using words from our current language. This is done by changing operators and key words from symbols into words or symbols that are common to our everyday language, like changing "for(int i = 0; i < 10; i++)" to "integer i = 0 \break repeat 10 times \break i = i + 1" [Pavlus, 2012]. Both examples have the exact same functionality, but change the assumed knowledge of for loop construction to words like "repeat" and "times." 

We agree with our previous argument that natural language, if implemented at all, should be implemented in a superficial way. That means that it is only replacing singular functions or key words and not trying to simplify the language. We think the inclusion of natural language into the design of a DSL is dependent on both the intended user and the domain that the DSL covers. If the language of the domain is very well defined and widely used, it would make sense to include parts of it to make understanding of the DSL easier. If the intended user of the language is use to languages that don't include natural language, it would make sense to leave it out of the DSL design. Basically our idea for when not to use it is to think of any ambiguity adding certain natural language into your DSL would cause when people would try to write or understand it. If there is any, don't include that natural language because the ambiguity will cause more harm than good. If there isn't any, then if inclusion of the natural language makes understanding the DSL code easier, include it. 

---

**Question**

Briefly describe how you split up the work for this assignment.

**Response**



---
