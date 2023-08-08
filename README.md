# Soccer Player Value Prediction
Link to original project class repo: https://github.com/COGS118A/Group018-Sp22

## Abstract
The goal of this project is to predict the financial value of a soccer player in the transfer market. The prediction is made by applying machine learning algorithms to a dataset containing various factors such as player performance, league participation, player position, and other relevant metrics. The insights derived from this analysis aim to shed light on the intricacies of player valuation in the world of professional football.

## Background
In the ever-changing landscape of professional football, understanding a player's financial worth in the transfer market is both complex and critical. This project embarks on a journey to unravel this complexity by employing algorithms that analyze a player's performance, age, playing position, and more. By delving into historical data and current market trends, the project aims to develop a predictive model that accurately gauges a player's value.

## Data
The dataset was meticulously collected from [Transfermarkt](https://www.transfermarkt.us/primera-division/marktwerte/wettbewerb/ES1), a reputable source for football statistics. It includes five variables, capturing essential aspects of a player's profile. The data are dynamic, with constant updates reflecting real-time changes. The observations are scrutinized and cleaned to ensure quality and relevance to the problem statement.

## Proposed Solution
The initial approach involved a linear regression model to find relationships between variables and predict the financial value of players. This method was chosen for its simplicity and effectiveness in modeling linear relationships. The data normalization process was also planned to accommodate nonlinear data, extending the model's applicability.

## Chosen Solution
After extensive discussions and analysis, the team shifted towards a more nuanced approach. The idea of predicting wages based on similarities between players resonated well with the project's objectives. Thus, a K-Nearest Neighbors (KNN) model was adopted. This model classifies players into different wage groups, considering various features that define a player's characteristics and performance.

## Evaluation Metrics
Evaluating the model's performance was carried out through a two-pronged strategy. The validation loss served as an immediate indicator of the model's fit, while the average difference between actual and predicted salaries provided a tangible measure of accuracy. A lower average difference was sought as a sign of the model's precision in predicting player salaries.

## Results and Analysis
The results were insightful, with the KNN model correctly classifying players on the wage spectrum's ends most of the time. This observation indicates the model's proficiency in discerning between highly paid and less paid players. Various visualizations and statistical analyses were conducted to interpret these results, providing a comprehensive understanding of the model's behavior and effectiveness.

## Ethics & Privacy
The ethical dimension of the project was carefully considered. The data, sourced from public domains and comprising game statistics and individual player performances, posed no privacy concerns. However, the team ensured that all data handling was conducted responsibly and transparently, adhering to best practices in data ethics.

## Conclusions and Discussions
The project's journey was marked by continuous learning, adaptation, and refinement. From the initial proposal to the final implementation, goals and methods were realigned to converge on a solution that made logical and practical sense. The resulting model stands as a testament to the team's commitment and ingenuity, offering a valuable tool for football analysts, clubs, and enthusiasts.

## Team Members
- Arturo Sorensen
- Emmanuel Gutierrez
- Hector Gallo
- Jai Mali
- Marco Paredes

## Future Work
The project opens avenues for future exploration and enhancement. Incorporating more features, tuning hyperparameters, and exploring different algorithms could lead to even more accurate predictions. Collaboration with industry experts and real-world testing are also on the horizon, promising exciting developments in the field of football analytics.
