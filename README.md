NaiveAi0
========

My naive attempt at building a generic framework in C# for playing around with AI.

This is the bare bones that allows the creation of an agent that takes percepts as input, processes them in a black box and returns actions. The idea is that each percept contains a dictionary of customisable name value pairs. The plan in future is that any kind of percepts can be fed in once implemented e.g. pixels, sounds, etc and clustering / pattern recognition etc can take place on this.

The plan is that eventually a realtime stream of percepts can be fed in, and actions output.


I know very little about AI. I did one AI unit in uni 10 years ago and have forgotten most of it. So this is really just for fun. Also I have absolutely no idea how I'd actually implement pattern matching, clustering etc so currently this is a framework to make playing with that stuff a bit easier.
