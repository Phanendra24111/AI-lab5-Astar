# AI-lab5-Astar

Implementation of A* Search for finding the optimal path from S to G using `f(n) = g(n) + h(n)`.

## My Approach

I used a queue storing `(f, g, path)` and always expanded the path with the smallest `f` value. Unlike Greedy Best-First Search, A* considers both the actual cost travelled `g` and the estimated remaining cost `h`, allowing it to find the optimal path `S → B → G` with cost `5`.

## Files

* `AI_LAB5.py` - the code
* `notes` - my handwritten notes for this lab

## How to run

```bash
python3 AI_LAB5.py
```

## Code Snippet of the output for the problem
<img width="992" height="255" alt="image" src="https://github.com/user-attachments/assets/cc393976-4430-4bb4-aaa0-fb796f2c006b" />
