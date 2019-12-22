# choose-the-best-team-based-on-skills

#### This was implemented under the valuable guidance of Prof David Crandall at Indiana University in B551 Elements of AI during Fall 2019.

In this, we had to get the whole number contribution of people which maximizes the sum of the skills and consumes no more than the cost stated.
Since the code that was written was adding fractional part we had to remove that line. Besides, taking the code in any priority order such as the one with maximum skill per unit cost may not work. Because, it can diminish the other high skill elements provided, and restrict some other small elements to be added. So, checking all the possible combinations with total cost less no more than the given cost and with no scope of adding any other element to it with cost still remaining greater than or equal to the given cost.

The first challenge that we faced was to create an exhaustive set of all the possible combinations of the people who were under the budget, and then we tried to maximize that set. On maximizing  we anticipated that we would get the final output, which unfortunately that was not the case because of the  set was too large to give the solution in optimal time.

Then we went on to add more rules to the above solution by ignoring the combinations which did not tend to maximize the skillset provided the cost was completely exhausted. 

#### To run the code

./choose_team.py people-small 200

200--- total budget
