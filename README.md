# Parler-Data-Merge
This is a little project where I decided someone should merge the 3 available Parler datasets to see what sort of overlap there is between them.
It proved more complex than I originally anticipated as one of the datasets was in the format of the raw html. Thus, I had to parse that with lxml (chosen for speed). Further complications were found in the fact that files became...too large to handle in memory. My solution to that was to switch to a line by line processing of the data.  
