# Kickstarter

Launched in 2009, Kickstarter has now became a world famous online crowdfunding platform. The platform mainly focus on creativity and merchandising, which has made some of the most fantastic ideas to come true.

The crowdfunding process is simple:

Project owners propose their projects and provide related information such as idea, pricing, schedule, etc.
Backers back the projects that seems attractive
The purpose of this kernel is to explore the data collected from Kickstarter, trying to understand some characteristics of the platform.

Summary of Research Questions:
1. What are the factors that contribute to a Kickstarter campaign’s success rate?
Result: number of backers is the most important predictor for the success rate for a
Kickstarter campaign, other factors that could have minor effect includes launch time and
country. The main category of projects could also affect backer’s preference or willingness to
support a project, and different countries have different trends in terms of the popularity of
crowdsourcing with the US having the highest backer support rate of successful projects.
2. What are the underlying trends of types of projects that backers are more willing
to support?
Result: backers are more likely to support game projects.
3. How accurate can a machine learning model predict the outcome of any project
given the current data? What are the most important features that contributes to
the accuracy of the predictions?
Result: a DecisionTreeClassifier is able to predict whether a project will be successful or
failed based on the goal amount, number of backers, main category of the project, launched
month of the project, and the duration of the campaign at approximately 92% accuracy, with the
goal amount and number of backers being the strongest predictor. If remove number of backers,
the prediction accuracy lowers to approximately 62%.
4. Do project success rate differ across different countries?
Result: US has the highest project success rate among all countries.
5. When is the most common time to launch a project on Kickstarter? Is this a major
contributor to the success or failure of a project, or are other factors more
important?
Result: the most common time to launch a project on Kickstarter is in July, the second
most common time is in March, and the least common time is in December. If only look at the
percentage of successful projects for each month, December has the lowest success rate, July
has the second lowest, while March has the highest success rate.

