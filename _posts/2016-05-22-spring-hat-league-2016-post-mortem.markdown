---
published: true
title: Spring Hat League 2016, Post-mortem
layout: post
---
Spring hat league 2016 wrapped up last week, so it's time to look at how my
predictions fared!

Let's jump straight in with the money plot.  This diagram shows the average
score differential per game for all of the teams in the "JP Mixed (4/3)"
division of spring hat league.  My team is highlighted by the red circle.  Yes,
that's us in the lower left corner of the diagram.  I projected my team to
finish near the bottom of the rankings, and we did.  I am proud and 
embarrassed at the same time.

![Average score differential per game vs. predicted
rating](https://github.com/sbussmann/buda-rank/blob/master/Code/SpringHat2016_validation.png?raw=true)

Another interesting feature of this diagram is the trend for teams with 
higher predicted ratings to have better score differentials.  This is 
compelling evidence in support of my methodology to rate BUDA teams.  I 
suspect that putting this rating system into production for hat 
league drafts would lead to more balanced teams than the current system.  To 
test this hypothesis, I need access to the ratings that BUDA currently uses 
for the draft.  I plan to contact BUDA to make this happen, with the eventual
 goal of implementing my ratings during hat league drafts.
 
One fun question we can ask right away is: how would my team have to change 
to become an average spring hat league team?  To answer this question, we 
need to know three things: 

 1. There are 16 players on each team.
 2. A fantastic player has a rating of about 1800.
 3. A complete novice has a rating of about 800.  
 
If we replaced the lowest rated player on our roster with a complete stud, our
team rating would go up by (1800 - 800) / 16 = 62.5 points.  My team's rating
would become about 1120 -- we'd be significantly below average, but not the
worst team in the league anymore.  We'd reach about 1180 with another stud --
enough to be solidly in the upper half of the league.  Studs don't just grow on
trees, so what if we added a "reasonably good player" (i.e., rating of about
1400)?  In this case, we'd need about 3 players to get up to league average.
 
In future posts, I plan to discuss

 - methods to improve my ratings
 - interesting teams (what's going on with the team with a predicted rating 
  of 1050 and a score differential of +7??)
 - comparison to existing BUDA rating system (if I get access to the data)
 - interesting trends with time in the BUDA database

> Note: In my last post, I ranked both the "JP Mixed (4/3)" and "Lexington Mixed
(4/3) Weekend" divisions, which is why I had 30 teams listed in the previous
post.

`huh`

```
x = y
```