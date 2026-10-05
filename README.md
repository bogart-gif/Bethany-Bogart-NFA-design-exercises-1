`Challenges`  
Problems #16 and #24 gave the most trouble because I was trying to figure out how to go about making the designs for these two more readable. I also had to redo some of #16 to address all valid strings.  

I chose some new problems to make NFA designs out of although I chose some simpler languages to keep the drawn out trees small.  

I worked to design the NFAs first before asking AI if there were any valid strings that might end up getting rejected. For one design, a slight issue came up which was when I followed up that thread with my revised design to see if that would pass the rejected but valid string.  

`Surprises/Mistakes`  
To me, I was surprised with how little some of these designs required, with most only needing 2-3 states. I had expected to do more work which was probably one of the reasons as to why this exercise was somewhat challenging.  

Not necessarily an entire next state subset but I didn't account for a certain string for #16, being "!0." I did not consider a valid path for when "q1" transitions to the initial and accept state "q0" through reading a 0 or 1. This was because I did not account for valid strings that don't end in 1, despite that not being a part of the language (I was only considering 101 or 10101 instead of 10 or 1010 initially).

To avoid making these mistakes it is best to draw out possible states that the NFA machine can actually reach, alongside making a list of valid strings and invalid ones before approaching the design phase. Planning these out would help to avoid issues that come from designing things for real world applications or just for future exams in this course.
