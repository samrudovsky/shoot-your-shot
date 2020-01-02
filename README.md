## Expediting skill development and professional growth of NBA rookies 

### Project 2 – Metis Data Science Bootcamp (Weeks 2-3)

**Technical Focus**
- Linear regression
- Web scraping

### Problem Statement 
Player development and salary cap management are arguably the most important jobs of an NBA front office and coaching staff.   

Rookie players play an outsized role in both situations. Rookies can roughly be grouped into three categories:
1) Rookies who have potential but are clearly not ready to compete at an NBA level, often because their body hasn't developed to compete with NBA players.  

2) Rookies, like Lebron James, who not only deserve playing time from the get-go, but make a an immediate positive impact on winning.  These players are rare. 

3) Rookies who are talented enough to compete in the NBA but are prone to mistakes and fluctuations in play.  This is the most common scenario.  coaches have a short leash – they prefer to have younger players in this third group play limited minutes and instead learn from veterans and from watching game tape. This is a theory of osmosis – the trust that rookies will be learn strong habits work ethic by soaking in the examples of veteran teammates. Others coaches throw the rookies into the deep end – they trust that the growing pains that may jeopardize the success of the team in the short-term will pay off in the long-term.

The NBA has a hard-cap, meaning that teams are not allowed to spend over a certain amount of money on their players.  The intention is to level the playing field between small market teams (such as Milwaukee) and big market teams (such as Los Angeles).  Organizations must make shrewd draft decisions and then have a good player-development staff in order to remain competitive year after year.  With older players often commanding higher salaries, it is incumbent upon an organization to develop young players on smaller contracts.  

Is it worth jeopardizing the team's success as a rookie works through the kinks? Or should only the most NBA-ready rookies command significant minutes? 

**Using statistics from the 1960s through the modern era – scraped from http://www.basketball-reference.com – I attempt to show that giving rookies ample opportunity to fail is generally a sound philosophy for NBA organizations**

---

### Project Goals

- Using the totality of a player's year-1 statistics, predict that player's points per game (PPG) in year 2
- Analyze patterns in the data that may offer valuable player development insight for NBA organizations

---
### Results

With an MAE of 2.7 points per game, the cross-validated linear model with an L1 regularization penalty made fairly robust predictions. Perhaps more importantly, the model offers strong evidence that coaches should be patient with their rookie players, even if their field goal percentage is low. 

**Players who had the opportunity to take a lot of shots (regardless of whether those shots went in at a high rate) often showed a marked improvement from year 1 to year 2**

The opportunity for rookies to shoot their shot (even when most shots were missed!) was  strongly associated with year 2 success.  In fact, it was far more predictive than a player's year 1 field goal percentage. NBA coaches, development teams, and front offices, should err on the side of patience when it comes to developing their young players. 
