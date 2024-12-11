---
title: Vocal Harmony Algorithms with Adapting Markov Chains and Shortest Paths
---
Brief Overview: Created harmony algorithms using 2, 4, 6, 8, and 16 voices using basic algorithms, then by appropriating Djikstra's Algorithm. Final iteration of the project used 4 layers of Markov Chains to achieve customizable textures with user commands. 

The design was: the user can press one button for the chord to play, and another for the desired texture. The program would read what current note values are, scan what possible destinations in other notes were valid given the user's chord input, and adjust the probability weight of each path to another note for each of the 4 voices sequentially based on the user's texture input, the last few notes that particular voice had played, and the current notes the other voices occupied. This was to achieve internal voice leading and to reduce monotony in the 12 tone scale.

For voice spectrum analysis, primarily relied on direct use of Short-Time Fourier Transforms (STFTs). Also as well as fixed-formant tracking to perform real-time vocal analysis and re-synthesis (it bricked my old computer at the time). Tried to implement floating-point formant tracking to normalize adjusted frequencies' amplitudes in different ways.