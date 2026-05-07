---
layout: page
title: Personal Projects
---

<div style="border:1px solid #d0d7de; padding:16px 20px; border-radius:10px; margin:20px 0; background:#f6f8fa; text-align:center;">

<h1 style="margin:0; font-size:1.5em;">
 Personal Data & Analytics Work
</h1>

</div>
These projects are built outside of my professional work and are focused on exploring machine learning, predictive modeling, and sports analytics.

Most of my interest sits at the intersection of data science and sports, especially MLB, NASCAR, and NHL, where I experiment with modeling player performance, game outcomes, and statistical trends. I’m also interested in how these ideas connect to real decision making, not just predictions on paper.


<div style="display:flex; justify-content:left; gap:14px; flex-wrap:wrap; margin:16px 0;">

<a href="/Personal Projects#WAR-Model" style="display:inline-block; padding:10px 16px; background:#000; color:#fff; border-radius:8px; text-decoration:none; font-weight:500;">
MLB WAR Prediction Model
</a>

<a href="/Personal Projects#nhl-goalie" style="display:inline-block; padding:10px 16px; background:#000; color:#fff; border-radius:8px; text-decoration:none; font-weight:500;">
Goalie Selection Model
</a>

<a href="/Personal Projects#Pit-Stop" style="display:inline-block; padding:10px 16px; background:#000; color:#fff; border-radius:8px; text-decoration:none; font-weight:500;">
Pit Stop Performance Analysis
</a>

</div>

---

<div id="WAR-Model" style="border:1px solid #d0d7de; padding:16px 20px; border-radius:10px; margin:20px 0; background:#f6f8fa; text-align:center;">

<h2 style="margin:0; font-size:1.5em;">
  MLB WAR Prediction Model
</h2>

</div>

Built a machine learning model to predict MLB player WAR using underlying offensive metrics and positional information.

<p align="center">
  <img src="images/WAR_Performance.png" width="500" style="border-radius:10px;">
</p>

WAR (Wins Above Replacement) is one of the most complete measures of player value, combining hitting, defense, and baserunning into a single number. This project explored how closely WAR can be estimated using only measurable underlying skills.

I used a linear regression model with player level features like barrel rate, walk rate, strikeout rate, exit velocity, launch angle, and positional adjustments to predict total WAR.

The results showed that offensive quality and plate discipline were the strongest signals. Barrel% and BB% had the largest positive impact, while strikeout rate was negatively correlated with value. Adding positional features also helped capture differences in defensive value across roles.

Overall, the model explained a meaningful portion of WAR variation (R² ≈ 0.60), showing that a lot of player value can be approximated from offensive and positional data alone.

<p align="center">
  <img src="images/WAR_Table.png" style="border-radius:10px;">
</p>

<a href="https://github.com/sieloffs/MLB-Analytics/blob/main/WAR%20Modeling.ipynb" 
   align = "center"
   target="_blank"
   style="display:inline-block; padding:8px 12px; background:#000; color:#fff; border-radius:6px; text-decoration:none;">
   Open GitHub Code
</a>

---

<div id="nhl-goalie" style="border:1px solid #d0d7de; padding:16px 20px; border-radius:10px; margin:20px 0; background:#f6f8fa; text-align:center;">

<h2 style="margin:0; font-size:1.5em;">
  Goalie Selection Model
</h2>

</div>

Built a machine learning model using millions of NHL tracking data points as part of a group project to explore how teams can make better goalie start decisions.

<p align="center">
  <img src="images/Goalies.jpg" width="500" style="border-radius:10px;">
</p>


Worked with a team of students at UNC Chapel Hill to develop a model that could help inform which goalie to start in a given game. The inspiration for this project came from debates around goalie selection during the 2026 Winter Olympics and how similar decisions play out in the NHL.

We built a rich feature set with over 100 potential variables, including advanced tracking metrics and exponential weighting techniques to emphasize recent performance over historical averages.

The goal was to create a system that could provide a meaningful edge in goalie selection at the NHL level. However, due to the high level of noise in goaltender performance from game to game, predictive power was limited.

Overall, the model performed slightly better than random selection, which reinforced how difficult short term prediction is in this space, but also highlighted the importance of feature design and how small signals can still exist in highly volatile environments.


<div style="display:flex; justify-content:left; gap:14px; flex-wrap:wrap; margin:16px 0;">

<a href="https://colab.research.google.com/drive/1xLgFPd02bLSix9enssZa6-FV2z_4aMkM?usp=sharing" target="_blank" style="display:inline-block; padding:10px 16px; background:#000; color:#fff; border-radius:8px; text-decoration:none; font-weight:500;">
Open Notebook
</a>

<a href="/images/Final_Report_DATA780.pdf" target="_blank" style="display:inline-block; padding:10px 16px; background:#000; color:#fff; border-radius:8px; text-decoration:none; font-weight:500;">
Full Report
</a>

</div>


---
<div id="Pit-Stop" style="border:1px solid #d0d7de; padding:16px 20px; border-radius:10px; margin:20px 0; background:#f6f8fa; text-align:center;">

<h2 style="margin:0; font-size:1.5em;">
  Pit Stop Performance Analysis
</h2>
</div>

Analyzed NASCAR pit stop performance to understand how pit crew execution impacts race outcomes in the 2024 season.


<p align="center">
  <img src="images/Pit Crew.jpg" style="border-radius:10px;">
</p>

Pit stops play a critical role in NASCAR, where races are often decided by fractions of a second. Even small mistakes on pit road can lead to significant position changes over the course of a race.

This project explored how pit stop efficiency relates to finishing position by analyzing stop times, positions gained or lost, and overall crew consistency.

Key findings showed that slow pit stops have a measurable impact on race results, with each slow stop associated with roughly one lost finishing position. Driver consistency over the season also emerged as a strong predictor of race outcomes, even more so than starting position in many cases.

<p align="center">
  <img src="images/Slow Stops.png" width="500" style="border-radius:10px;">
</p>

<a href="https://github.com/sieloffs/NASCAR-Analytics/blob/main/Data%20720%20Final%20Project.ipynb" 
   target="_blank"
   style="display:inline-block; padding:8px 12px; background:#000; color:#fff; border-radius:6px; text-decoration:none;">
   Open GitHub Code
</a>


---


<div style="display:flex; justify-content:left; gap:14px; flex-wrap:wrap; margin:16px 0;">

<a href="/Work Projects" style="display:inline-block; padding:10px 16px; background:#000; color:#fff; border-radius:8px; text-decoration:none; font-weight:500;">
Work Projects
</a>

</div>
