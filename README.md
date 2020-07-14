# Degrees

## Built with Python 
According to the Six Degrees of Kevin Bacon game, anyone in the Hollywood film industry can be connected to Kevin Bacon within six steps, where each step consists of finding a film that two actors both starred in.

This program finds the shortest path between any two actors by choosing a sequence of movies that connects them. For example, the shortest path between Jennifer Lawrence and Tom Hanks is 2: 
Jennifer Lawrence is connected to Kevin Bacon by both starring in “X-Men: First Class,” and 
Kevin Bacon is connected to Tom Hanks by both starring in “Apollo 13.”

Thi is framed as a search problem: the states are people. The actions are movies, which take us from one actor to another. The initial state and goal state are defined by the two people we’re trying to connect. 

By using breadth-first search, we can find the shortest path from one actor to another.
