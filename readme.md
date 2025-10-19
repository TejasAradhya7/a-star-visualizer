I built this project because I wanted to see an algorithm think.

Most of the time, pathfinding is something that happens quietly inside a computer. We know it works, we know it’s efficient, but we rarely get to see how it reasons its way through a problem. The A* algorithm, in particular, has always fascinated me — the way it balances exploration and intuition, searching just enough of the unknown to find the best possible path.

This visualizer turns that process into something you can watch and interact with. You draw walls, set a start and an end, and then the algorithm begins to move — patiently, step by step — mapping out possibilities until it finds the shortest route. The animation slows things down just enough for you to see the logic unfold in real time. Every decision, every step, is visible.

Technically, the project is simple by design. It’s a single-page application written in JavaScript, using a custom Min-Heap to make the algorithm efficient. The grid supports eight directions of movement, with diagonal steps measured by true distance. The canvas resizes automatically for any screen, and the performance metrics appear as the algorithm runs, showing exactly how much work it’s doing to solve the puzzle.

But beyond the details, this project is about curiosity. It’s about watching a piece of logic behave almost like something alive — probing the world, backtracking, and eventually finding its way. I like to think of it as a small, digital experiment in clarity: a way to show that even in something as mechanical as an algorithm, there is a trace of intention, a rhythm of discovery that feels familiar.

You can open the file in any browser and try it yourself. It’s self-contained, responsive, and ready to explore.

At its heart, this project isn’t just about A*. It’s about what happens when an idea moves from theory into motion — when the abstract becomes visible, and the invisible becomes understandable.
