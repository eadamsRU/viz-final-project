# final-project

### Due December 18th 2023 by 11:59pm

The final project for data visualziation involves creating a dashboard (or a set on mini-dashboards) within Jupyter. We want to identify some set of rich data either from a live source or from a scientific publication, and provide the viewer with a means to explore the data and perhaps a means to compute some statistics or measures on the data. You will need to verify your data source and ensure that there is enough data to work with. *Enough* is subjective, and so do not hesitate to reach out with questions. Remember that data analysis may have unexpected, or unremarkable, conclusions. If your results are not what you expect, not exciting, or otherwise useless, *that is ok*. The point of this project is to tell a story, and sometimes stories are boring.

The project should be presented as a formal analysis of whatever topic/data you decide to cover. You are expected to site references, sources, and and more. Failure to properly site the work of others is considered plagiarism. While you will undoubtedly seek the internet for help with your code, your submission must be your own original code and not just a mashup of the work of others. Using ChatGPT and/or other AI tools to assist in your project are strictly prohibitive.

## My Abstract

I will be analyzing the game of Magic the Gathering to show the differences between colors and which color is best for the game format Cube. Cube in Magic is a format where players form a pod and draft their decks from a pre-designed set of cards to create a deck that they will use in a bracket styled tournament to determine the winner based on wins and losses. What goes into this is a best of 3 series between opponents to advance in the cube. There are different colors in Magic which are better in certain mechanics, and some cards work will with others based on mechanics, abilities, creature types, etc. So it is important to see which cards get picked early and if there is any clear winner from a cube of what you should prioritize. Think of the draft as drafting a sports team like fantasy football, you need to pick cards for all different 'postions' that all play their part to benefit the end goal.

A possible future/other insight would to be if there is a correlation between real world monetary value and high-value cube cards. I will be using a 'Vintage' cube list as the data set as there tends to be a standard of what cards are best in Magic's history to be used in this format. 

## Grading

Given the complexity of the project and the potential complexity of the dataset, it is difficult to lay out specific requirements and criteria. You will be graded on the structure of your notebook(s), quality of data cleansing/preparation, and usefulness of the visualizations and interactivity. Notebooks shall act as presentations, written and designed such that a user with no knowledge of your project topic should be able to understand the material and make clear conclusions.

Code should be clean and efficient, documentation should be thorough and well written, and visualizations should be informative and conclusive. You will not be graded on the *style* of your code.

### Core Requirements

To receive full credit, at a minimum your project much abide by the following:

* The project is submitted via GitHub
* The project is submitted on time
* The project shall be submitted as a Jupyter Notebook (or series of Notebooks)
* The project shall work seamlessly in *tortugashell*; the Conda environment that powers the GitHub Codespaces in this course

If there are libraries/modules you wish to use that are not available in our cloud environment, please let me know as soon as possible and I will get them added.

### Examples from Previous Students

* Taylor Swift Album Release Effects on Spotify - live data from Spotify's data API was recorded for the weeks leading up to and after the release of Taylor Swift's album *Red (Taylor's Version)*
* Steam Player Behaviors - live data from Steam's data API was recorded hourly for a select number of games for the months of October and November to show behavioral patterns of gamers
* Magic the Gathering Rules Complexity - dataset of all cards was used to attempt to show how the complexity of the game has increased over the years by associating rules complexity with the word counts for every card.
* COVID-19 Pandemic Spread - COVID-19 infection rates for counties across the USA from mid 2020 through mid 2021 were interatively visualized to show the fluctuations of infection hotspots
