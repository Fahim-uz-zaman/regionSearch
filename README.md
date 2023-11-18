# regionSearch

The task is to develop a computational method or algorithm to identify and analyze influential regions within a given graph. 
These influential regions are defined as subsets of nodes or subgraphs that have a significant impact on the overall structure. 
The influential region have to be connected.

![261865436-0ee3a759-5366-49b4-be07-96b0b24a8ea3](https://github.com/Fahim-uz-zaman/regionSearch/assets/84631705/7691a4d3-43fe-4b14-a856-0eff23ca7cb3)


# Most Influential Region Search


## Project Overview

-   Statement: We are given a graph, in that graph for every node there is some positive reward point, and for every edge there is some edge cost. We have to find out a connected subgraph which has the total edge cost less than our given maximum budget.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Graph Algorithms](#graph-algorithms)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Graph Generation:** Create graphs with ease and flexibility.
- **Edge weight assignment:** Assigning random weight to each edge in the graph.
- **File Writing:** Writing graph data to a text file.
- **Plot Graph:** Pictorial representation of  graph.
- **Greedy Algorithm**: Greedy approach to solve the problem

## Getting Started

To get started with the Graph Algorithms Project, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/fahim-uz-zaman/graph-algorithms-project.git
    ```

2. Navigate to the project directory:

    ```bash
    cd graph-algorithms-project
    ```

3. Install dependencies:

    ```bash
    npm install  # or yarn install
    ```

## Usage

The project provides a simple command-line interface (CLI) for running various graph algorithms and visualising their results.

## Graph Algorithms

### Depth-First Search (DFS)

In incremental greedy algorithm, we start from a empty subgraph and form every vertex we will try to expand our subgraph , side by side we will take care of the edge capacity and the connectivity.

We perform the checking for every vertex present on that graph, and when we get the maximum reward point we update our resultant graph.


### Branch-And-Bound (BB)


In the brunch and bound algorithm, we start from an empty set and we explore all the subgraphs that can be formed for our graph. Then we check only for the subgraphs that are connected and has the total edge capacity less then our given budget.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests. Please follow the [contribution guidelines](CONTRIBUTING.md).
