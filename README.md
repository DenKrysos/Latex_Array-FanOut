# Latex_Array-FanOut

Defines an Array-alike Data Structure in Latex and a Fan-Out Mechanism for it.

First, you can fill in some Data sequentially into the Array (FIFO).
Afterwards, using the FanOut-Macro they are spilled out again and fanned-out.

Application:
Define a Set of Data once, use it multiple Times

Use-Case Example:
I used it to Write some Anime-Reviews. Each Review comprised the Title and a Review-Text. These Tupels are filled into such an Array.
In a second step, I printed first a "short Ranking List", i.e. only the Anime-Titles ranked, no description Text.
In a succeeding section, every Anime is printed in the same order, where it shows additionally the review text.
