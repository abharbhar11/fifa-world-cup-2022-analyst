About the Project

This is a personal side project analyzing FIFA World Cup 2022 match data using Python in Google Colab, with AI assistance. The goal is simple: look for patterns in the data and statistically test some common football beliefs, such as "does high possession make a team more dangerous?"

It is exploratory and made for learning, not formal research. This repository contains the code documentation of that analysis.

Questions Explored
What do goals and possession look like across the tournament?
Are teams with more than 60% possession more efficient at turning shots into goals?
Is a team's number of defensive pressures related to its opponent's possession?
Which teams scored the most and conceded the least, and how did they play?
Are fouls and cards related to defensive solidity?
Key Findings
An average of 2.69 goals per match across 64 matches.
High possession was not shown to improve goal conversion (p = 0.84).
Defensive pressures correlate strongly with opponent possession (r = 0.84), largely because a team without the ball naturally defends more.
Best defenses: Brazil, Morocco, Spain, England, and the Netherlands, with quite different defensive styles.

⚠️ All results are correlations within a single small tournament and do not prove causation.

Tech Stack

Python, pandas, NumPy, SciPy, Matplotlib, Seaborn, Google Colab

🙏 Acknowledgements

Many thanks to die9origephit for collecting and openly sharing the FIFA World Cup 2022 Complete Dataset on Kaggle. This learning project would not have been possible without your effort and generosity. Thanks also to the Kaggle community for making data like this accessible to everyone.

All rights to the data remain with the dataset creator and original sources. Please check the dataset page on Kaggle for the applicable license.
