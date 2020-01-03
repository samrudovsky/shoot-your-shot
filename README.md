# Shoot Your Shot – Expediting skill development and professional growth of NBA rookies 

## Project 2 – Metis Data Science Bootcamp (Weeks 2-3)

### Technical Focus
- Linear regression
- Web scraping

---

### Problem Statement 
Player development and salary cap management are arguably the most important jobs of an NBA front office and coaching staff.   

Rookie players play an outsized role in both situations. Rookies can roughly be grouped into three categories:
1) Rookies who have potential but are clearly not ready to compete at an NBA level, often because their body hasn't developed to compete with NBA players.  

2) Rookies who make an immediate positive impact on winning.  These players are rare. 

3) Rookies who are talented enough to compete in the NBA but are prone to mistakes and fluctuations in play.  This is the most common scenario.  There are two general philosophies surrounding the management of these players. The first is a theory of osmosis – the hope that rookies will learn strong habits and work ethic not by playing significant minutes but by careful observation of the example set by their veteran teammates. The second theory encourages throwing the rookies into the deep end with the hope that inevitable short-term growing pains will lead to accelerated growth. 

The NBA has a hard-cap, meaning that teams are not allowed to spend over a certain amount of money on their players.  The intention is to level the playing field between small market teams (such as Milwaukee) and big market teams (such as Los Angeles).  Organizations must make shrewd draft decisions and then have a good player-development staff in order to remain competitive year after year.  With older players often commanding higher salaries, it is incumbent upon an organization to develop young players on smaller contracts.  

Is it worth jeopardizing the team's success as a rookie works through the kinks? Or should only the most NBA-ready rookies command significant minutes? 

**I scraped 60 years of statistics from https://www.basketball-reference.com: That data indicates that allowing rookies ample opportunity to fail is generally a sound philosophy for NBA organizations**

---

### Project Goals

- Using the totality of a player's year-1 statistics, predict that player's points per game (PPG) in year 2
- Analyze patterns in the data that may offer valuable player development insight for NBA organizations

---
### Results

With an MAE of 2.7 points per game, the cross-validated linear model with an L1 regularization penalty made fairly robust predictions. In addition, the model offers strong evidence that coaches should be patient with their rookie players, even if their field goal percentage is low. 

**Rookies who were allowed sufficient opportunity to shoot the basketball (regardless of whether those shots went in at a high rate) often showed a marked improvement from year 1 to year 2**

The opportunity for rookies to shoot their shot (even when most shots were missed!) was strongly associated with year 2 success.  In fact, it was far more predictive than a player's year 1 field goal percentage. NBA coaches, development staff, and front offices should err on the side of patience when it comes to developing their young players. 
