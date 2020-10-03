# Background

> A* (pronounced "A-star") is a graph traversal and path search algorithm, which is often used in many fields of computer science due to its completeness, optimality, and optimal efficiency.
> — _referenced from Wikipedia_

`Worst-case Time Complexity:` ![Worst-case Time Complexity](https://render.githubusercontent.com/render/math?math=O(|E|)=O(b^{d}))

`Worst-case Space Complexity:` ![](https://render.githubusercontent.com/render/math?math=O(|V|)=O(b^{d}))

</br>

As an informed variation of Dijkstra, `A*` is considered a `best first search` because it greedily chooses which vertex to explore next, according to the value of ![](https://render.githubusercontent.com/render/math?math=f(v)=h(v)%20%2B\%20g(v)), where ![](https://render.githubusercontent.com/render/math?math=f) is the heuristic and ![](https://render.githubusercontent.com/render/math?math=g) is the cost so far.

## Python Implementation

![](res/fast.gif)

![](res/med.gif)

![](res/slow.gif)
