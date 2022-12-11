# Multi-Collision-Search

This paper presents an algorithm for collision search that could very well be extended to solve multi-collision search problem. The algorithm uses a stack-based cycledetection algorithm as a precursor. The stack based cycle detection algorithm has
traditionally been known to provide time-memory trade-off. Performance reaches close
to the theoretically best performance when multiple stacks are used in the precursor
algorithm at the cost of increased memory usage. Our algorithm for collision search
problem can also be parallelized in the final step. Average case time complexity has
been the sole parameter of analysis in this paper, which is another reason why the
stack-based algorithm has been used for cycle detection.
