# LoL---Personal-Gameplay-Data-Analysis
**Author**: David Tian

## Overview
What kind of actionable insights can I take away from analyzing my personal gameplay data? As a player that only plays one champion (Kayle OTP), I wanted to focus on my ranked games with Kayle, to see if there were any findings that could positively influence my gameplay and help me climb the ranked ladder.

## Preconceived notions
Due to the nature of Kayle being a hyper-scaling, late-game orientated champion, I had several preconceived notions I wanted to test:
1. Damage dealt to champions would be higher in wins than losses
2. Creep score per minute was higher in wins
3. Chances for winning would increase as games dragged on


In addition to verifying whether these preconceived notions were correct, I also analyzed which champions I play well with, which champions I play poorly against, and whether there were any players that I play well with/poorly against.

## Preconceived Notion 1
Claim: Damage dealt to champions would be higher in wins than losses

![image](https://miro.medium.com/max/682/1*h2dzOsMyV8N0pI90YPGGQw.png)
![image](https://miro.medium.com/max/594/1*6Zju_KIhfwb6wQCeY5cfLg.png)

~2,600 more damage dealt to champions in wins, statistically significant

Confirmed: damage dealt to champions is significantly higher in wins than losses.

## Preconceived Notion 2
Claim: Creep score per minute was higher in wins

![image](https://miro.medium.com/max/663/1*A63li98LW9MNaBsD8qA6qQ.png)
![image](https://miro.medium.com/max/579/1*_coLVAJLJhu6kxQykLljuw.png)

~7cs/minute in wins, statistically significant

Confirmed: cs per minute is significantly higher in wins than losses. <br>
As a side note, looking at the violin plot, it looks like I’m almost certain to lose games where I’m only getting 4cs/minute.

## Preconceived Notion 3
Claim: Chances for winning would increase as games dragged on

![image](https://miro.medium.com/max/663/1*wOPXPJZcJdw1gkJvk21erQ.png)
![image](https://miro.medium.com/max/570/1*zc-GIW_nbEpsC4VUfQNUnw.png)

Debunked: game duration is not statistically different between wins and losses

## Further Exploration: Red Side or Blue Side?
In League, the blue side has historically seen a slight advantage simply due to map imbalances relative to objectives. I was curious to see if this was applicable to me — maybe I performed better on a certain side of the map. While I observed that I won 3% more games when on the red side, was this difference statistically significant, or is this by random chance? I used a chi-squared test to determine that there was, in fact, no statistical difference between the red side and blue side when it came to my win-rate.

![image](https://miro.medium.com/max/631/1*UAK7uHKvRrFXWH0LFISvJw.png)

## Further Exploration: Champion Win Rates
After testing to see if my preconceived notions were true, I wanted to see if there were certain champions that I played better with. The graph below shows champions that I’ve found the most success playing with.

![image](https://miro.medium.com/max/700/1*tHvkjfT04_T64FM_1HXNwA.png)

Some of these champions aren’t surprising to me — Khazix and Udyr are extremely meta picks right now, whereas Samira/Yasuo/Yone/Twitch are champs that Kayle synergizes well with. I was surprised to see that Jhin was on this list, as I don’t picture great synergy with Kayle. <br>

Now, let’s look at my lowest win-rates against certain enemy champions.

![image](https://miro.medium.com/max/700/1*Qlngp1dGmy1S43IrHbve2A.png)

Because I play Kayle top lane, I focused on the two Top lane champions: Nasus and Sett. The fact that Nasus is one of the worst champions for me to play against confirms my experience with the matchup: I find myself having to run away from him at all stages of the game, even when ahead. It was interesting to me to see Sett on this list, as I don’t feel like it’s a hard matchup currently. I think this can be explained by the fact that Sett is often seen in the bottom lane as a support, so really the key takeaway here is to avoid Nasus.

## Further Exploration: Other Players
As you climb higher and higher on the ladder, the size of the player pool decreases, so you often times find yourselves playing with, or matched up against the same players. This brought the question: are there certain players I don’t play well with?

![image](https://miro.medium.com/max/384/1*W3l7Nl2PYG6jdlNO6TJ0Lg.png)

Looking at this, I might think to myself, “avoid these players”. Interestingly enough, ‘Shower or League’ is the Twitch streamer Hanjaro, and it’s particularly funny to see him on this list because I actually remember playing really badly in our games together… so bad to the point where he reported me for intentionally feeding. So maybe the takeaway here is that I owe these players a win.
