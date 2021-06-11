---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 600

title: Competition rules
subtitle: Do you really want to know?

content:
  # Page type to display. E.g. post, talk, publication...
  page_type: rules
  # Choose how many pages you would like to display (0 = all pages)
  count: 5
  # Filter on criteria
  filters:
    author: ""
    category: ""
    tag: ""
    exclude_featured: false
    exclude_future: false
    exclude_past: false
    publication_type: ""
  # Choose how many pages you would like to offset by
  offset: 0
  # Page order: descending (desc) or ascending (asc) date.
  order: desc

design:
  # Choose a view for the listings:
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view: 2
---

# Rules

STV's Euro Cup competition consists of two parts:

* 14 questions related to various more or less observables that are found at
https://nettskjema.no/a/205067 

* An Excel form, in which the outcome of each game has to be forecasted, estimates, guessed, place-your-verb-here. The form was distributed by Dagfinn in an email Thursday June 3rd.

The excel form consists of 36 games in the group stage and 15 games in the knockout stage. The schedule for the 36 group stage games is set and those games are specificed in the left part of the form.

The first game is between Turkey and Italy. There are two cells between the two, and we fill in what we believe is the final score. We then repeat this until the game between Portugal and France

When the score for all group stage games are filled in, the magic of Excel will automatically fill in the games in the Round of 16. We then move on to put in the scores in these games as well, which in turn will populate the Quarter finals.

We repeat this for quarter-finals, semi-finals and, finally, the final final. 

The grey cells in group stage games 25 thorugh 36 and in the knockout rounds are for penalty shoot-outs. You may fill in these as well, but they have no relevance for the outcome of the competition. 

##  Points

* Points are awarded for each and every correct answer to the 14 questions. In addition, we calculate the total number of goals scored in the form for a 15th question "How many goals will there be in total? (Penalty shoot-outs excluded)". Each of these questions yield 30 points, for a total of 450 for the questions section

* Points are earned for guessing the correct outcome of each of the games in the group stage. Each correct answer is worth 25 points, for a total of 900 points

* Points are _deducted_ for any deviance between the predicted and observed scores. As usual in the Social Sciences, we square the deviance. If the first game is predicted a 2-0 Turkey victory over Italy but ends in a 4-1 Turkish victory, then 25 points are awarded for the correct outcome, before (4-2)<sup>2</sup>=2<sup>2</sup>=4 and (1-0)<sup>2</sup>=1<sup>2</sup>=1 points are deducted for slightly missing the correct result. In the end, 25 - 4 - 1 = 20 points are awarded. 

* Points are earned in the the knockout round for guessing the correct teams in each of the knockout stages. 25 points are awarded for each correct team, and a bonus 5 points if the team appears on the correct spot in the playoff schedule. Correctly guessing both teams in a knockout game will thus give (25 + 5) * 2 = 60 points. With 15 knockout games, the total points available is 900.

* Finally, 200 points are awarded for correctly guessing the winner of the Euro2021 cup. 

The theoretical top score is therefore 2450 points.

# Changes from 2018

Previously, the score of the knockout stage games had no say on the competition, as only the teams at each stage yielded points. The 15th question, "How many goals will there be in total?", means that the score estimated in the knockout stage will influence the total number of goals scored, as this answer will be computed based on the Excel forms.