[The ToBI system is a method in linguistics used to annotate emphasis in speech.](https://www.cs.columbia.edu/~julia/files/conv.pdf) By denoting where the direction and magnitude of rising or falling tones in recorded speech fall, as well as the break indices (essentially, the magnitude of the speaker's pauses, which are indicative of the rhythm and pronunciation of the speech), the ToBI system allows linguists to visually represent the sonic gestures of a speaker's accents, intention, and overall pronunciation.


The method for this project combines the use of the [CMU Pronunciation Dictionary](http://www.speech.cs.cmu.edu/cgi-bin/cmudict) with [PyToBI](https://github.com/monikaUPF/PyToBI) to derive test analytics in ToBI notation of the gestural qualities of Irish texts written in English. 

Comparing these test analytics with ToBI analytics derived by hand from audio of recitations of the same texts reveals discrepancies in how the CMU Pronunciation Dictionary derives tonal analyses of texts when the vernacular the text was written in is different than Standard American English.

This is not a flaw of the CMU Pronunciation Dictionary, so much as it is a gap in what tools have been developed for detecting and representing tonal qualities in different dialects of English -- tonal qualities which hold a fundamental bearing over what the text is saying.


The project seeks to produce a tool capable of creating pronunciation dictionaries and derivative tools for tonal analysis for different vernaculars of a language. By using the soundbyte analysis methods of PyToBI in conjunction with Machine Learning and a large enough sample size of recordings of a people with a common vernacular reading a selected text, we could create an abstract archive of that vernacular's speech habits. 

This could aid endeavors in digital humanities, especially where Irish literature is involved, considering their historical reliance on oral poetry. After all, this project arose out of [James Joyce](obsidian://open?vault=ITPportfolio&file=Gestural%20Measures%20in%20Vernacular%20and%20NLP%20-%20References)'s own work. 

Furthermore, this project has the potential to produce analytic tools for academic work concerning [American and other vernaculars of English that are often underrepresented](https://www.deepcenter.org/deepcenter/wp-content/uploads/2017/08/three-ways-to-speak-english-by-jamila-lyiscott.pdf). There is also the long term possibility of this tool deriving analytics to represent the gestures in pronunciation of languages other than English, which would involve underrepresented global communities in the necessary academic work.

#project 
backlinks: [[Gestural Measures in Vernacular and NLP]], [[Gestural Measures in Vernacular and NLP - Synopsis]], [[Gestural Measures in Vernacular and NLP - References]]