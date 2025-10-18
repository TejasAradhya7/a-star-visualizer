A* Pathfinding Visualizer (Optimized)

A responsive, single-page web application demonstrating an optimized implementation of the A* search algorithm. This project showcases proficiency in core computer science algorithms, optimized data structures, and front-end development using vanilla JavaScript and HTML Canvas.

 Key Technical Features

This visualization is built to perform efficiently, directly demonstrating advanced algorithmic knowledge:

Optimized Data Structure (Min-Heap):

The openSet (priority queue) is custom-implemented using a Min-Heap, ensuring that extracting the node with the lowest F-cost is an efficient $O(\log N)$ operation. This is a critical performance optimization over typical $O(N)$ linear searches.

Advanced Path Calculation (8-Directional Movement):

The algorithm supports movement in all eight directions (cardinal and diagonal).

Path costs are accurately calculated: 1.0 for cardinal steps and $\text{Math.SQRT2}$ ($\approx 1.414$) for diagonal steps, ensuring the path found is truly the shortest distance in Euclidean space.

Performance Profiling and Observability:

The aStar function includes built-in performance tracking using performance.now().

The UI displays the total search time and the number of nodes explored, providing real-time observability into the algorithm's efficiency for any given grid configuration.

Responsive UI:

The application is fully responsive, utilizing Tailwind CSS for layout and dynamically resizing the Canvas based on the viewport size, ensuring usability on desktop and mobile devices.

💻 How to Run

This is a self-contained, single-file project (index.html).

For Local Use: Simply download the index.html file and open it in any modern web browser.

For Deployment (GitHub Pages): Upload the index.html file to a GitHub repository. Enable GitHub Pages for the repository, setting the source to the main branch. The app will be live instantly.

🛠️ Usage Instructions

Draw Walls: Click and drag on the grid to toggle cells into walls (dark gray).

Set Start/End: Click the "Set Start (S)" or "Set End (E)" buttons and then click the desired cell on the grid. The mode will automatically revert to "Wall Drawing."

Run: Click the "Run A*" button to start the animation.

Results:

Visited Nodes turn light blue.

The final Shortest Path turns amber.

The status message displays the search time and complexity metrics.