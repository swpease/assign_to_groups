# assign_to_groups
Optimally assign people to limited-sized groups.

This is for the situation where you have people rank which groups (e.g. schedule slots, workshop topics, project topics) they want to join, but the groups have a maximum capacity, so some people may have to be given their second or third (or worse) choice.

The notebook has two basic sections:
  1. Transforming the data into the form required by the actually useful code.
  2. The assignment into optimized groups.

For the actual optimization, I copied over the code from this [C# solution](https://gitlab.com/darrylm/assign_to_workshops), which answered this [StackOverflow question](https://stackoverflow.com/questions/48467666/ranking-optimization).

The code isn't super generalizable. I've included a dummy .csv so you can see what form of data is required for the pandas manipulations I used. I'm not sure how much sense the names will make in the future, because I mostly copied names from the aforementioned C# code, but changed a few that made it easier for me to link to the data I was working with.
