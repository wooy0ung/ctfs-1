## silent & silent2
Both of the challenges can be solved by smallbin's double free loophole. According to host, the silent should be solved by fastbin attack~ So careless, should I say it?
And the worse is the interaction with the programs, that's the worst I've ever seen. It makes me stuck for all afternoon. I've been debugged the program. And after the competition is over, I successfully exploited it~Junk, Junk, Junk!

## note
Giving libc.
So its exploit way is related to malloc_cosolidate().
Just read the source code of realloc.