---
title: Vocal Harmony Algorithms with Adapting Markov Chains and Shortest Paths
---
*Topics: Markov Chains, Shortest Paths Algorithms, Voice Spectrum Analysis, Fourier Transform*
***
Brief Overview: Created harmony algorithms using 2, 4, 6, 8, and 16 voices using basic algorithms, then by appropriating Djikstra's Algorithm. Final iteration of the project used 4 layers of Markov Chains to achieve customizable textures with user commands. 

The design was: the user can press one button for the chord to play (the tonic, the subdominant, etc.), and another for the desired texture. 

First the program would read what notes are currently voicing. Next, it would scan what other possible notes serve as valid destinations given the user's chord input. With that data, it would then adjust the probability weight of each path to another note for each of the 4 voices sequentially based on: 1) the user's texture input, 2) the last few notes that particular voice had played, and 3) the current notes the other voices occupied. This was to achieve internal voice leading and to reduce monotony in the 12 tone scale.

For voice spectrum analysis, the program primarily relied on direct use of Short-Time Fourier Transforms (STFTs) as well as fixed-formant tracking to perform real-time vocal analysis and re-synthesis (it bricked my old computer at the time). Tried to implement floating-point formant tracking to normalize adjusted frequencies' amplitudes in different ways.