---
title: Modeling Transverse Wave Interference Patterns in 2D and 3D with VR for Learning Fundamentals of Wave Behavior and Integration in Physical Modeling of Acoustic Membranes
---
*Topics: VR as a Learning Tool, Multidimensional Approach to Learning and Representation, 2D Wave Equations, Fourier Transform, Physical Modeling Sound Synthesis*
***
Overview:

This tool's use cases split in two: audio synthesis, and visual representation. 

The project seeks to use visual models of wave interference patterns both for physical modeling synthesis and to serve as a learning tool in approaching wave equations.

The current implementation of this tool creates two kinds of maps to visually represent 2D transverse wave interference patterns in an ideal euclidean plane. The first is a node map, which shows harmonic patterns that emerge from the waves' collision (like a chladni plate). The second is a heatmap, which shows the distribution of energy throughout the antinodes. The user can visually see these maps and manually play with the parameters to watch how the interference patterns and energy levels shift and self-organize.

To achieve physical modeling synthesis of acoustic membranes (and, possibly, wind instruments), the program would scan the data from the heatmap, then use Fourier Analysis to synthesize a series of frequency/amplitude pairings to recreate the sound being played. By setting fixed parameters and having the program sweep through them with appropriate decay rates, this program could reasonably visually model, mathematically analyze, and sonically synthesize the transients and pitches of a snare drum or other percussive instrument. 

If the program could make the leap to modeling bell-like shapes, rather than shapes in square or circular planes (which might be explored with either multivariable calculus or hyperbolic geometry, depending on the limitations of the tool's implementation), the program may be able to synthesize cymbals. 

A future step could be modeling wind instruments, using integration (and maybe heuristics) to represent texturally intricate sheets of air particles rising in a column of air (like a pipe organ).

Aside from this practical use in audio engineering, I think the possibility for this program to serve as a visual learning tool for physics is more enticing. What happens if we expand the wave equation from 2D to 3D? What happens when we make the tool a VR environment that users could roam around in as they play with the parameters? What happens if we reverse the sound synthesis process with STFTs to create an audioreactive program that can represent sounds visually as they change in a highly descriptive way? If we do this, and add an extra dimension, this would surely make for an interesting audiovisual performance art tool -- but does it have an educational use? 

Could the program model longitudinal waves rather than transverse waves? What would it take to implement rules to mimic induction and model harmonic distortion in electric flux? 

I'm aware most of these questions (if not all of them) break down at a certain point for some intricacy I didn't consider -- that is why I'm so in love with this project. I don't know what those intricate details about 2D and 3D waves are, and I want to learn what they are and how they work.