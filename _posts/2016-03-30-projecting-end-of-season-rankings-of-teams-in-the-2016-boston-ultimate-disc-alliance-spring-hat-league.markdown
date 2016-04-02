---
published: true
title: Projecting end-of-season rankings of teams in the 2016 Boston Ultimate Disc Alliance spring hat league.
layout: post
---
I am playing on Team 20 in this year's Boston ultimate frisbee spring hat league.  Open spots for men in spring hat league fill up completely within an hour of registration starting, so I was super excited to get a roster spot.  Almost immediately after I got the confirmation email on March 22 that I was in the league, I began to wonder how good my team was going to be.  

> Disclaimer: This is hat league, in which players are (mostly) randomly assigned to teams.  The primary purpose of the league is to have fun playing ultimate frisbee.  I fully adhere to the principle that winning is secondary here.  

With the disclaimer out of the way, I will admit that I am compulsively interested in quantifying talent at ultimate frisbee.  Fortunately, the Boston Ultimate Disc Alliance ([BUDA](http://buda.org)) records the score of every game played in all leagues.  The roster for every team is available as well.  Game scores and rosters can be used to generate and assign a rating to every player in the database.  

Over the past week, I scraped the BUDA website using [BeautifulSoup](http://www.crummy.com/software/BeautifulSoup/), built the player rating database, and ranked each of the teams in spring hat league.  Check out the python code [here](https://github.com/sbussmann/buda-rank/blob/master/Code/scrape-buda.ipynb) that does all of this.

The upshot?  My assertion that winning is a secondary goal will be put to the test; I'm projecting team 20 to finish 25th out of 30.  Yikes!

![Team 20 Projection](https://github.com/sbussmann/buda-rank/blob/master/Team20Rating.png)

Here is the full set of projected rankings.  The season starts tonight!  Looking forward to testing my projections!

 19. Team 2
 1. Team 3 
 21. Team 11 
 26. Team 14 
 13. Team 23 
 23. Team 10 
 10. Team 13 
 20. Team 19 
 2. Team 24 
 0. Team 21 
 9. Team 22 
 17. Team 30 
 24. Team 6 
 7. Team 12 
 22. Team 17 
 8. Team 8
 5. Team 18 
 3. Team 9 
 11. Team 16 
 28. Team 15 
 29. Team 26
 4. Team 25
 12. Team 7
 18. Team 1 
 15. Team 20 
 27. Team 4 
 25. Team 29 
 14. Team 5 
 16. Team 27 
 6. Team 28 

