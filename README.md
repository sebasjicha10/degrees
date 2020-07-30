# Degrees

## Built with Python - Graph search algorithms
Program running: https://youtu.be/sDNTEbUArMM

## How to run (example)

```
$ python degrees.py large
Loading data...
Data loaded.
Name: Emma Watson
Name: Jennifer Lawrence
3 degrees of separation.
1: Emma Watson and Brendan Gleeson starred in Harry Potter and the Order of the Phoenix
2: Brendan Gleeson and Michael Fassbender starred in Trespass Against Us
3: Michael Fassbender and Jennifer Lawrence starred in X-Men: First Class

```

According to the Six Degrees of Kevin Bacon game, anyone in the Hollywood film industry can be connected to Kevin Bacon within six steps, where each step consists of finding a film that two actors both starred in.

This program finds the shortest path between any two actors by choosing a sequence of movies that connects them. For example, the shortest path between Jennifer Lawrence and Tom Hanks is 2:<br />
Jennifer Lawrence is connected to Kevin Bacon by both starring in “X-Men: First Class,” and<br /> 
Kevin Bacon is connected to Tom Hanks by both starring in “Apollo 13.”<br />

This is framed as a search problem: the states are people. The actions are movies, which take us from one actor to another. The initial state and goal state are defined by the two people we’re trying to connect. 

By using breadth-first search, we can find the shortest path from one actor to another.
