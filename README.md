# Social Network Analyses of ETEC565A Discussion Forums

![](https://avatars1.githubusercontent.com/u/66854558?s=96&v=4)
A visualization of different facets of the course discussion forums in ETEC 565A.

## A network of people

These networks visualize the interactions in the forums constituted by posting and replies to posts. Individuals whose posts received no replies are therefore not represented.

[Task 1 People](t1-people)

[Task 2 People](t2-people)

[Task 4 People](t4-people)

[Task 5 People](t5-people)

## A network of ideas

TF-IDF was calculated for each unique post (regardless of interaction). Then, every post was compared against every other post looking at the cosine similarity of their tf-idf scores. The result was expressed as a network of similarity of ideas; only the top half of the full range of similarities was mapped in the network graph.

[Visualization of Task 1 Posts' contents](t1-posts)

[Visualization of Task 2 Posts' contents](t2-posts)

[Visualization of Task 4 Posts' contents](t4-posts)

[Visualization of Task 5 Posts' contents](t5-posts)
