# hack-ucsc-project
News bias detecting software.
Hi everyone! Here is the source code for the project that I made for the 2015 UCSC hackathon.
This project takes a primary source and finds the parts of that source which WEREN'T included inside
a news article and returns the excluded portions to the user in handy HTML format. It uses a hashtable
to find the starts of sequences and then finds the greatest common subsequences between the two texts by
looking at the edit distance between those two segments. It kind of works in the same way that plagiarism 
detection software works, but in this case we want the reporter to include as much of the original material as
possible.

This is just the code that went into the body of the program and doesn't include the rest of the solution 
(I'm going to polish it and release it as freeware.) You can modify this code or use it for yourself as 
you see fit. It's got a few warts, but it works.
