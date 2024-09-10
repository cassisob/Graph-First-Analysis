# Challenge: Discover the Wonderland of Graph Networks

This test was provided by a Brazilian company for a job interview.

## The Graph Dataset

The dataset for this challenge is available in the `alice_graph.csv` file. It contains information about the connections within *Alice's Adventures in Wonderland*.

In this graph, nodes represent characters, and edges represent interactions. A connection between two characters indicates that they interacted in some way throughout the book.

## The Quest

The goal is to explore this graph and uncover intriguing insights.

# Deliverable

The results of the challenge are provided in the `graph_data_analysis.ipynb` file.

## Pre-requisites

The required Python libraries to run the notebook are listed below. Use `pip install <name of library>` to install all dependencies.

```python
# for manipulating datasets
import pandas as pd

# for manipulating graphs
import networkx as nx
# for detecting communities
from networkx.algorithms import community

# for showing plots
import matplotlib.pyplot as plt
