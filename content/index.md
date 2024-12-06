---
title: Home
---
***
Welcome to my portfolio! Think of this website as an open space you can traverse in whatever order seems appropriate. To traverse the space, click the hyperlinks embedded in text that looks like [this](https://kabir-daniel.github.io/itp_mps_application_portfolio/Hyperlink-Poetry-as-3D-Essay-Writing-for-Alternative-Scholarship)
***
Technical Research Interests:
- Voice Spectral Analysis
- Networks and VR for Audiovisual Performance and Composition Environments
- Physical Modeling with 2D Waves
- Generative Musical Performance
- VR as a Modality for Representation and Learning
- Alternative Musical Instrument Design Integrating Software and Hardware (Inspirations: Auerglass, Hyperbass)
***
Theoretical Research Interests:
- Anarchival Practice
- Poetics and Relation
- Philosophy of Law
- Metaphysics
- Language, Performance, Grammar, and Ethics
- Performative Methods for Alternative Scholarship
- Public Memory, Space/Place, Rhetorical Ecology, and Rhetorical Cartography
***





***
# Projects
***

- *Below each project title is an overview of that project.* 

- *For full specifications of a project, including references, click on the hyperlink embedded in the project title. (Coming Soon)*

- *Some words in the descriptions also have hyperlinks to provide more context when needed. (Coming Soon)*

- *Each project has a subheading describing what kind of project it is. You can click on each of the subheadings to read about my interest in using them as methods of althernative scholarship. (Coming Soon)*

***



***
### Gestural Measures in Vernacular with NLP 

##### *Language Analysis Tool and Critical Argument*

Topics: Machine Learning, Voice Spectrum Analysis, the Sound Object and Language, Representation in Education, Gesture, Performance, Accessibility in Representation

Overview:
This project began in conjunction with Berkeley's Data Lab as a digital humanities project in Professor Catherine Flynn's class on AI and Irish literature. 

Combining methods in linguistics and data science with voice spectrum analysis, this project purports to visually represent the gestural quality of language in written text using the ToBI System. 

By combining standard Natural Language Processing tools (like the CMU Pronunciation Dictionary) with a program which used STFTs to analyze rhythmic and tonal inflections in speech, I created a program that could analyze written text and output a ToBI annotation visually representing the sonic gesture of what the text was saying. 

Initially, this project was an inquiry into whether or not the gestures of language could be analytically represented through the lens of the sound object. However, upon implementation of the program, I found a different problem: the CMU Pronunciation Dictionary does not accurately represent the sonic qualities of particular vernaculars of English (such as vernaculars or dialects of English spoken in Ireland). 

Finding writings from David Foster Wallace, James Joyce, and Dante Alighieri which critiqued representation (or lack thereof) for vernaculars of a language in Academia inspired me to further research this question of representing the sound object in language and its bearing on gestures in speech and written text. 

The future of this project involves using machine learning to analyze particular dialects and automatically generate pronunciation dictionaries for that demographic's usage of the language at hand, then visually representing the melodic and rhythmic gestures that arise in reading a text in that dialect to draw our attention to what differences may arise.
***

  
  
***
### Modeling Transverse Wave Interference Patterns in 2D and 3D with VR for Learning Fundamentals of Wave Behavior and Integration in Physical Modeling of Acoustic Membranes 

##### *Audiovisual Performance and Learning Tool*

Topics: VR as a Learning Tool, Multidimensional Approach to Learning and Representation, 2D Wave Equations, Fourier Transform, Physical Modeling Sound Synthesis

Overview:
This tool's use cases split in to: audio synthesis, and visual representation. The overall project seeks to use visual models of wave interference patterns to serve as a method of physical modeling synthesis, and to serve as a learning tool in approaching wave equations.

The current implementation of this tool creates two kinds of maps to visually represent 2D transverse wave interference patterns in an ideal euclidean plane. The first is a node map, which shows emergent harmonic patterns that emerge from the waves' collision. The second is a heatmap, which shows the distribution of energy throughout the antinodes. The user can visually see these maps and manually play with the parameters to watch how the interference patterns and energy levels shift and self-organize.

To achieve physical modeling synthesis of acoustic membranes (and, possibly, wind instruments), the program would scan the data from the heatmap, then use Fourier Analysis to synthesize a series of frequency/amplitude pairings that would recreate the sound being played. By setting fixed parameters and having the program sweep through them with appropriate decay rates, this program could reasonably visually model, mathematically analyze, and sonically synthesize the sizzle of a snare drum, or the rumble of a timpani. If the program could make the leap to modeling bell-like shapes, rather than shapes in square or circular planes (which might be explored with either multivariable calculus or hyperbolic geometry, depending on the limitations of the tool's implementation), the program may be able to synthesize cymbals. The leap to modeling wind instruments may be a similar progression of the tool, probably using integration (and maybe heuristics) to represent texturally intricate sheets of air particles rising in a column of air (like a pipe organ).

The visual aspect of this project may be more interesting from a research perspective. What happens if we expand the wave equation from 2D to 3D? What happens when we make the tool a VR environment that users could roam around in as they play with the parameters? What happens if we reverse the sound synthesis process with STFTs to create an audioreactive program that can represent sounds visually as they change in a highly descriptive way? If we do this, and add an extra dimension, this would surely make for an interesting audiovisual performance art tool -- but does it have an educational use? What if we could make the program model longitudinal waves rather than transverse waves (which have different properties, like rarefactions vs. troughs)? Could we implement rules to mimic induction and use this tool to explore harmonic distortion in electric flux? I'm aware most of these questions (if not all of them) break down at a certain point for some intricacy I didn't consider -- that is why I'm so in love with this project. I don't know what those intricate details about 2D and 3D waves are, and I want to learn what they are and how they work.
***



***
### Vocal Harmony Algorithms with Adapting Markov Chains and Shortest Paths 

##### *Musical Performance and Language Analysis*

Topics: Markov Chains, Shortest Paths Algorithms, Voice Spectrum Analysis, Fourier Transform
Brief Overview: Created harmony algorithms using 2, 4, 6, 8, and 16 voices using basic algorithms, then by appropriating Djikstra's Algorithm. Final iteration of the project used 4 layers of Markov Chains to achieve customizable textures with user commands. 

The design was: the user can press one button for the chord to play, and another for the desired texture. The program would read what current note values are, scan what possible destinations in other notes were valid given the user's chord input, and adjust the probability weight of each path to another note for each of the 4 voices sequentially based on the user's texture input, the last few notes that particular voice had played, and the current notes the other voices occupied. This was to achieve internal voice leading and to reduce monotony in the 12 tone scale.

For voice spectrum analysis, primarily relied on direct use of Short-Time Fourier Transforms (STFTs). Also as well as fixed-formant tracking to perform real-time vocal analysis and re-synthesis (it bricked my old computer at the time). Tried to implement floating-point formant tracking to normalize adjusted frequencies' amplitudes in different ways.
***



***
### [Hyperlink Poetry as 3D Essay Writing for Alternative Scholarship](https://kabir-daniel.github.io/itp_mps_application_portfolio/Hyperlink-Poetry-as-3D-Essay-Writing-for-Alternative-Scholarship)

##### *Alternative Scholarship*

Topics: "Unflattening", Poesis, Literature, Criticism
***



***
### Reverb and Transverse Interference Patterns in 4D 

##### *Audiovisual Performance Tool*
***



***
### Network-Based VR Audiovisual Composition and Performance Environment

##### *Audiovisual Performance Tool*
***
  

  
***
### Gray Code Interface 

##### *Musical Performance Tool*

Topics: Musical Instrument Design, AltCS, Woodworking, Mechatronics, Way of the Hand

I find the construction of tools and theories guided by what use can be derived from the work's production limits the possibility of what the work can become. As such, I've grown fond of what I call Alternative Computer Science -- uses of Computer Science that are more fun and creative than they are useful. Examples of AltCS include the intentionally inefficient systems of the esolang community, the gemini protocol, and grey code. 
Grey code in particular is pretty awful for efficient computing -- but it makes a great interface for a musical instrument. With just 4 buttons, 4 keystrokes can do the work of 15, and the way grey code enumerates is far more intuitive for the hand to learn with push buttons with 4 fingers than for binary. Adding a 5th button for the thumb to work control could make for a fascinating number of microtonal synthesizers with their own compositional biases (heuristics, if you will) deriving from the ergonomics of the hand and how the player approaches learning grey code by way of the hand. I would also like to incorporate this idea into a mechatronic bridge system to alter tuning while playing the piccolo bass, in my ongoing quest to acquire a more affordable hyperbass.
***




### Identity Occlusion: Discourse's Collapse in Measuring Dialectic Monologues and the Tyranny of Representation 

##### *Performance Piece*
***



***
# Sound Sculptures
***



***
### On the Map Room: Cartography as Speculative Figure Drawing for Anarchival Practice 

##### *Sound Sculpture*


Historically, map rooms served as a locus for information and power. Today, maps still inform and govern our ordinary lives. Maps guide map users in traversing or interpreting a space. 

  

Whether it's a literal map -- like in urban planning or legislative districts -- or an abstract map -- memory, or an archive, or the space of literature, or the space of law --, the map delimits for those who rely on it the possibility of how they could imagine or encounter the space. 

  

My argument for this relies on Nick Sousanis's Zithers -- skeletal lines he uses in designing a comic book page, governing the order in which the reader encounters the argument and determining how the reader's attention will be allocated -- and Ramona Naddaff's reading of Plato's *Republic* -- which delves deep into the nuances of how foundational myths control the possibility of what a state can become.

  

  

The sculpture itself for "On the Map Room" is a map room full of different maps represented in different ways. Some can be interacted with, giving the audience a sense of agency in encountering the map; others are fixed for them beforehand. Each unique map is accompanied by a written piece, serving as a critical lens into ways of imagining space, relation, and representation. Relevant topics will span from non-euclidean spaces, to maps of the cold war, and further.

  

Inspired by Heidegger's "Triadic Conversation" -- the character of the guide, in particular --, the space of the map room is itself a space to be traversed and interpreted, but there is no map for how to navigate the map room. Each audience member must make their own way for themselves.

  

"Speculative Figure Drawing" incorporates arguments of speculative thinking with Barthes's writing on fragments, figures, and discursis. This creates a foundation for criticism concerning presence/absence in (an)archival theory as a matter of traversal (space, time, relation). 

***



***
### Confrontation: The Tree of Law 

##### *Sound Sculpture*


"The Tree of Law" is a sculpture modeled after the scale that is the symbol for Columbia's Education Graduate Program, "Teachers College". This is the institution which gave us both Nick Sousanis's *Unflattening* and Lucy Calkin's infamous balanced literacy curriculum. 

The installation lives in an enclosure that looks like a hanging bird cage. The cage is bifurcated by a line of taught harp strings, anchored at the top of the birdcage and the diameter on the floor. The audience may step into one half of the cage to be confronted with what stands on the other side of the barrier -- the "Tree".

The "Tree" is a large sculpture inspired by the Teachers College symbol. The "T" figure in the Teachers College symbol serves as the trunk for "The Tree of Law", which represents a balance scale -- a universal symbol for law and justice. However, instead of balance pots hanging by wire from the branches of the "T", long, heavy gauge copper induction coils extend down and forward. In the induction coils are two earbuds, each playing its own note. The notes are controlled by a dialectic melody machine similar to one I made based on Chomsky's syntactic structures in undergrad. In short, the earbuds are playing notes that complete each other -- but they are too high up to hear. The audience member must reach up and pull down one of the "fruits" to hear what it is saying -- and, in doing so, the other rises out of reach.

This project seeks to explore thought put forward by Sousanis's *Unflattening*, Tauba Auerbach's "Auerglass", and more in an inquiry and criticism into metaphysics of education, law, and ethics.

  
This is a working draft of the hyperlink poem that would accompany the work:

"Confrontation is facing together. We recall that a face is a mask. A mask makes present by facing a face outward, concealing a face within. What a mask makes present is the character the body masked embodies in its performance. We cannot come to know the being at hand by the sight we're faced with; what we see is an illusion that lets us believe what character in front of us exists, seen through our eyes. Whether we come to know the being not in the light of reason but in the shadows of cognition's illuminations is not at hand -- we are, the technology of time. We are transient -- that aspect of the sound object that makes it characteristic of itself, in sound and essence. We forget our own existence -- that's how it stands out: by its passing on to the next tone or silence. We are stereoscopic, that's what lets us bind at all -- relation, exigence in context. Language is difference in motion, forgetting happening by memory's recognitions and releasement. We move about unmoving anchors in natural waters, plastic sound in stereo."
***
