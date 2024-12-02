---
title: Gestural Measures in Vernacular and NLP
draft: false
tags:
  - project
---
 
## Synopsis

A lack of representation for particular issues of difference in language have resulted in [issues in academia and popular literacy](obsidian://open?vault=ITPportfolio&file=Gestural%20Measures%20in%20Vernacular%20and%20NLP%20-%20References). 

I stumbled into one particular issue concerning data science and vernacular in my studies of Irish literature: the nuances of dialects and vernaculars of English are not considered by the current popular tools for Natural Language Processing (NLP) of English texts. As a result, the gestural measures of those texts are misrepresented when deriving analytics using NLP tools.

This project approaches the representation of the unique gestural qualities of a language's vernaculars using the [ToBI System](obsidian://open?vault=ITPportfolio&file=Gestural%20Measures%20in%20Vernacular%20and%20NLP%20-%20Method%20%26%20Construction).


## Method and Construction

[The ToBI system is a method in linguistics used to annotate emphasis in speech.](https://www.cs.columbia.edu/~julia/files/conv.pdf) By denoting where the direction and magnitude of rising or falling tones in recorded speech fall, as well as the break indices (essentially, the magnitude of the speaker's pauses, which are indicative of the rhythm and pronunciation of the speech), the ToBI system allows linguists to visually represent the sonic gestures of a speaker's accents, intention, and overall pronunciation.


The method for this project combines the use of the [CMU Pronunciation Dictionary](http://www.speech.cs.cmu.edu/cgi-bin/cmudict) with [PyToBI](https://github.com/monikaUPF/PyToBI) to derive test analytics in ToBI notation of the gestural qualities of Irish texts written in English. 

Comparing these test analytics with ToBI analytics derived by hand from audio of recitations of the same texts reveals discrepancies in how the CMU Pronunciation Dictionary derives tonal analyses of texts when the vernacular the text was written in is different than Standard American English.

This is not a flaw of the CMU Pronunciation Dictionary, so much as it is a gap in what tools have been developed for detecting and representing tonal qualities in different dialects of English -- tonal qualities which hold a fundamental bearing over what the text is saying.


The project seeks to produce a tool capable of creating pronunciation dictionaries and derivative tools for tonal analysis for different vernaculars of a language. By using the soundbyte analysis methods of PyToBI in conjunction with Machine Learning and a large enough sample size of recordings of a people with a common vernacular reading a selected text, we could create an abstract archive of that vernacular's speech habits. 

This could aid endeavors in digital humanities, especially where Irish literature is involved, considering their historical reliance on oral poetry. After all, this project arose out of [James Joyce](obsidian://open?vault=ITPportfolio&file=Gestural%20Measures%20in%20Vernacular%20and%20NLP%20-%20References)'s own work. 

Furthermore, this project has the potential to produce analytic tools for academic work concerning [American and other vernaculars of English that are often underrepresented](https://www.deepcenter.org/deepcenter/wp-content/uploads/2017/08/three-ways-to-speak-english-by-jamila-lyiscott.pdf). There is also the long term possibility of this tool deriving analytics to represent the gestures in pronunciation of languages other than English, which would involve underrepresented global communities in the necessary academic work.


## Stakes

The relevance of this project seeks to promulgate tools for Natural Language Processing in academic work that consider the vernaculars and dialects of thinkers whose language doesn't fit with Standard Written English conventions.

This idea has existed in academic work for centuries.

Dante Alighieri wrote on the distinction between academically recognized standard language and the people's language -- vernacular --, calling vernacular more noble than eloquent language.

In *The Portrait of the Artist* as a Young Man, James Joyce wrote on his language use feeling inferior to that of the Academy because of his vernacular's grammar and pronunciation. In Chapter 5, he wrote: "The language in which we are speaking is his before it is mine. How different are the words home, Christ, ale, master, on his lips and on mine! I cannot speak or write these words without unrest of spirit. His language, so familiar and so foreign, will always be for me an acquired speech. I have not made or accepted its words. My voice holds them at bay. My soul frets in the shadow of his language."

My study of these two sources' writing on vernacular in education made me privy to this issue, but it was a combination of David Foster Wallace's critique and my own experience with teaching English Language Arts to 9th Graders in the Bronx last summer that made apparent for me how much the lack of consideration for the nuances of vernacular in language education for younger students is serious issue.

 In his essay "Authority and American Usage", David Foster Wallace provided a nuanced critique of both descriptivism and prescriptivism. His argument against the prevalence of Standard Written English and prescriptivism in the schoolyard was particularly influential in my own teaching experience, and revitalized my interest in this project.

I hope to one day see this project to grow into a technical expansion of Jamilla Lyiscott's work toward legitimizing vernaculars and dialects of English as integral parts of academic writing.


## Steps Taken

I began this project in an English class with Professor Flynn in my last year at Berkeley. The class was called "AIrish" and focused on combining literary analysis with methods in digital humanities with the support of Berkeley's Data Lab.

I chose to focus on using Natural Language Processing (NLP) to create visual analytics of the sonic gestures of the texts we were reading. This arose out of my interest in [the sound object in philosophy](obsidian://open?vault=ITPportfolio&file=Sound%20Sculpture) and [[The Importance of Color, the Blind, and the Deaf in Philosophy]].


My method involved using the CMU Pronunciation Dictionary to tokenize a play by W.B. Yeats and derive a ToBI representation of its sonic gestures, then contrasting that with a ToBI datamap derived from actual recitation.

My resulting findings were that the NLP tools I could access were insufficient for accurately deriving analytics solely from visual text.


## Next Steps

The next steps of this project require me to get much better at Machine Learning (ML). The only experience I have with ML comes from [a project I did with Dr. Jeremy Wagner's guidance at Berkeley's Center for New Music and Audio Technologies (CNMAT)](obsidian://open?vault=ITPportfolio&file=Vocal%20Harmony%20Algorithms%20with%20Adapting%20Markov%20Chains%20and%20Shortest%20Paths). 


First, I would need to get a sufficient sample size of recorded audio reciting a selected text, from which I could derive a tool capable of generating a gestural pronunciation dictionary using PyToBI.

After that, I would need a sufficient sample size of a different vernacular (for example, English speakers with an Irish accent) to perform the same process with. 

As the PyToBI tool would derive faithful analytics, I would put the second tool through rigorous testing until it reached the same level of accuracy for its own vernacular. The result would be a program that could tokenize written text into either "Standard American ToBI Pronunciation" or "Standard Irish ToBI Pronunciation". 

The next step from there would be to make this process replicable for whatever vernaculars we could get the required audio samples from in order to derive an appropriate tool for them.


Without a doubt, this project will be an extremely long term one, which I will need both guidance and better technical skills for. I intend to integrate it someday into the [[Sound Sculpture]] for [[On the Map Room: Cartography as Speculative Figure Drawing for Anarchival Practice]].

## What's Missing (Section Incomplete)


## Related Projects

- [[Vocal Harmony Algorithms with Adapting Markov Chains and Shortest Paths]]
	- About a year prior to working on [[Gestural Measures in Vernacular and NLP]], I spent a lot of time playing around with creating vocal harmonizers and harmony algorithms. Creating algorithms which traversed the spectrum of harmony in music by heuristics opened my eyes to the possibility of what can be done with machines that can analyze sound, chart patterns, and learn. Without that work, I wouldn't have known how to proceed with [[Gestural Measures in Vernacular and NLP]].

- [[Generative Dialectics from Syntactic Structures]]
	- In my work with digital humanities, [[Gestural Measures in Vernacular and NLP]] was the successor to the project I had completed in Professor Okiji's class the semester prior -- [[Generative Dialectics from Syntactic Structures]] --, wherein I created a music machine that served as my first foray into making semiotic machines to represent and critique language use practices.

- [[Sound Sculpture]] for [[On the Map Room: Cartography as Speculative Figure Drawing for Anarchival Practice]]
	- The final form of [[Gestural Measures in Vernacular and NLP]] will be an integrated component in the [[Sound Sculpture]] I propose titled [[On the Map Room: Cartography as Speculative Figure Drawing for Anarchival Practice]].


## References


References for commentaries on underrepresentation of vernacular in academic history:


[Dante Alighieri's "De Vulgari Eloquentia]((https://www.danteonline.it/english/opere.asp?idope=3&idlang=UK) 


James Joyce's *[The Portrait of the Artist as a Young Man](https://www.gutenberg.org/files/4217/4217-h/4217-h.htm#link2HCH0005)* 


David Foster Wallace's "[Authority and American Usage](http://www.jamesgerity.com/biblio/authority.pdf)"


[Jamilla Lyiscott](https://www.deepcenter.org/deepcenter/wp-content/uploads/2017/08/three-ways-to-speak-english-by-jamila-lyiscott.pdf) is a modern proponent for the integration of vernaculars or dialects of English into modern academic language.


[This article discusses a current issue which demonstrates how certain demographics of students' struggles with literacy in America are in part linked to a lack of rigor in teaching the nuanced intersection between written and spoken language.](https://www.chalkbeat.org/newyork/2023/2/14/23598611/nyc-schools-reading-instruction-teachers-college-lucy-calkins-balanced-literacy-david-banks/)









