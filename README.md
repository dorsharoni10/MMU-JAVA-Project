# MMU-Java-Proj

In this project we simulate MMU. I've did cached page algorithms, that i wrapped it in a jar file.
Including random, LRU, second chance in the most effective time complexity.

Then I built a generic class that chooses which algorithm to choose. And saves the cache data in memory. If it does not find it in memory it goes to hard disk (in our case file) and takes it out of there to the cache.

And then packed everything on the client side in the mvc methodology.
