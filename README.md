# cse422-assignment-2--learning-and-decision-tree-solved
**TO GET THIS SOLUTION VISIT:** [CSE422 Assignment 2- Learning and Decision Tree Solved](https://mantutor.com/product/cse422-practice-problem-set-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115266&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE422 Assignment 2- Learning and Decision Tree Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Part 1: Short Calculation.

1. You are building a decision tree to predict whether a person will vote in an election based on their age group (18-30, 31-50, 51+), income level (Low, Medium, High), and interest in politics (Low, Medium, High).

The dataset contains the following distribution:

● 50 people in the 18-30 group: 30 vote, 20 do not vote.

● 40 people in the 31-50 group: 35 vote, 5 do not vote. ● 30 people in the 51+ group: 10 vote, 20 do not vote.

Question 1.1 Compute the Entropy of the given dataset.

Question 1.2 Compute the Conditional entropy of Age Group.

Question 1.3 Compute the information gain if you were to split the data based on the age group.

Suppose another attribute “Interest in Politics” with the following distribution:

● 60 people have low interest: 15 vote, 45 do not vote.

● 30 people have medium interest: 25 vote, 5 do not vote. ● 30 people have high interest: 35 vote, 0 do not vote.

Question 1.2 Calculate the information gain if you split the dataset based on “Interest in

Politics.”

Question 1.3 Between “Interest in Politics” and “Age Group” which attribute should be in the root node of the decision tree.

2. A bank wants to predict if a customer will default on a loan based on their credit score (Low, Medium, High) and previous loan history (Good, Bad).

The dataset has the following distribution:

● 40 people with Low credit score: 10 default, 30 do not default.

● 35 people with Medium credit score: 5 default, 30 do not default. ● 25 people with High credit score: 1 default, 24 do not default.

Question 2.1 What is the entropy of the dataset before the split, and what is the information gain when you split based on credit score?

Another attribute, “Loan History,” has the following distribution:

● 50 people with Good loan history: 5 default, 45 do not default. ● 50 people with Bad loan history: 25 default, 25 do not default.

Question 2.2 Calculate the information gain for splitting the dataset based on loan history.

3. A factory is predicting whether a machine will fail based on temperature (Low, Medium, High) and maintenance frequency (Regular, Irregular).

The distribution for the “Temperature” attribute is as follows:

● 30 machines operate at low temperature: 5 fail, 25 do not fail.

● 40 machines operate at medium temperature: 20 fail, 20 do not fail. ● 30 machines operate at high temperature: 25 fail, 5 do not fail.

Question: What is the information gain if you split the dataset based on temperature?

Now, consider the “Maintenance Frequency” attribute:

● 60 machines have regular maintenance: 10 fail, 50 do not fail. ● 40 machines have irregular maintenance: 40 fail, 0 do not fail.

Question: What is the information gain for splitting based on maintenance frequency?

Part 2: Constructing Decision Tree

Disclaimer: All of these dataset are fake and made for simulation purposes only.

For the following training datasets construct the full decision tree using the ID3 algorithm (shown in class). Show and explain all the steps of the ID3 algorithm using your work.

Dataset 1: This is a dataset of 14 records with features as age group, employment status, interest in community events and the class variable is Participation. Using this dataset as your training set and the ID3 algorithm, construct the decision tree to identify from these features if a person will participate in an event or not. Show all steps.

Attributes:

● Employment Status: Employed (E), Unemployed (U)

● Interest in Community Events: Low (L), Medium (M), High (H)

Target Variable

● Participation: Yes or No.

Age Group Employment Status Interest in Community Events Participation

Middle-aged Employed Medium Yes

Middle-aged Employed Low No

Middle-aged Unemployed Medium No

Senior Employed High Yes

Senior Unemployed Low No

Senior Unemployed Medium No

Senior Employed Low No

Middle-aged Unemployed High Yes

Senior Unemployed High Yes

Dataset 2: This dataset focuses on analyzing factors that influence whether women feel safe in their workplace. The key attributes include Workplace Environment (supportive, neutral, hostile), Harassment Policies (strong, moderate, weak), Workplace Flexibility (high, medium, low), availability of Health Benefits (yes, no), and the presence of Workplace Safety Measures (yes, no). The target variable is Feeling Safe, which indicates whether a woman feels secure in her work environment (yes or no).

Attribute Summary:

● Workplace Environment: Supportive, Neutral, Hostile

● Harassment Policies: Strong, Moderate, Weak

● Workplace Flexibility: High, Medium, Low

● Health Benefits: Yes, No

● Workplace Safety Measures: Yes, No

Target Variable:

● Feeling Safe: Yes or No

Workplace Environment Harassment

Policies Workplace

Flexibility Health Benefits Safety Measures Feeling

Safe

Supportive Strong High Yes Yes Yes

Hostile Weak Low No No No

Neutral Moderate Medium Yes Yes Yes

Supportive Strong Medium Yes Yes Yes

Hostile Weak Low No No No

Neutral Moderate High Yes No No

Supportive Strong Medium Yes Yes Yes

Neutral Weak Medium No No No

Hostile Moderate Low No No No

Supportive Strong High Yes Yes Yes

Neutral Moderate Low Yes No No

Hostile Weak Low No No No

Supportive Strong High Yes Yes Yes

Neutral Moderate Medium No Yes Yes

Dataset 3: This dataset is focused on predicting whether a computer science student will have a successful career based on several behavior-related attributes such as Study hours per week, Project experience, Internship experience, Extracurricular Involvement, Networking efforts.

Study

Hours per

Week Project Experience Internship Experience Extracurricular

Involvement Networking

Efforts Successful

Career

High High Yes High High Yes

Medium Medium Yes Medium Medium Yes

Low Low No Low Low No

High Medium Yes High Medium Yes

Medium Low No Medium Low No

Low Low No Low Low No

High High Yes Medium High Yes

Medium Medium Yes High Medium Yes

Low Medium No Medium Low No

High High Yes High High Yes

Medium Medium Yes Medium High Yes

Low Low No Low Low No

High High Yes High High Yes

Medium Low No Medium Low No

Attribute Summary:

● Study Hours per Week: Low (0-10 hours), Medium (10-20 hours), High (20+ hours)

● Project Experience: Low, Medium, High (based on the number and complexity of projects completed)

● Internship Experience: Yes, No (whether the student has completed an internship)

● Extracurricular Involvement: Low, Medium, High (participation in clubs, hackathons, etc.)

● Networking Efforts: Low, Medium, High (attending events, meeting professionals, etc.) Target Variable:

● Successful Career: Yes or No (based on factors such as securing a good job, advancing in the field, or achieving academic goals)

Dataset 4: This dataset focuses on predicting which type of crop—Cereal Crops, Vegetable Crops, or Fruit Crops—will grow best on a particular piece of farming land. The attributes include Soil Type (sandy, clay, loam), Water Availability (low, medium, high), Sunlight Exposure (low, medium, high), and Fertilizer Use (low, medium, high).

Soil Type Water Availability Sunlight Exposure Fertilizer Use Best Crop to Grow

Loam High High Medium Fruit Crops

Sandy Low High Low Cereal Crops

Clay Medium Medium Medium Vegetable Crops

Loam Medium High High Fruit Crops

Sandy Low Medium Low Cereal Crops

Clay Medium Low Medium Vegetable Crops

Loam High Medium High Fruit Crops

Sandy Low Medium Low Cereal Crops

Clay High Medium Medium Vegetable Crops

Loam Medium High Medium Fruit Crops

Sandy Medium High Medium Cereal Crops

Clay Medium Medium High Vegetable Crops

Loam High Low Medium Fruit Crops

Sandy Low High Low Cereal Crops

Clay Medium Low Medium Vegetable Crops

Attribute Summary:

● Soil Type: Sandy, Clay, Loam (the type of soil that affects crop growth)

● Water Availability: Low, Medium, High (the availability of water for crops)

● Sunlight Exposure: Low, Medium, High (the amount of sunlight the land receives)

● Fertilizer Use: Low, Medium, High (the amount of fertilizer applied to the land)

Target Variable:

● Best Crop to Grow:

○ Cereal Crops.

○ Vegetable Crops. ○ Fruit Crops.

Part 3: Conceptual Understanding

Find out the answer to the following questions.

1. What is the difference between supervised learning and unsupervised learning?

2. What is a training dataset, and why is it important in machine learning?

3. How does a machine learning model learn from data?

4. What is the purpose of splitting a dataset into training and test sets?

5. What is overfitting in machine learning, and how can it be prevented?

6. What is the role of a loss function in machine learning?

7. What is the difference between classification and regression?

8. What is the main objective of the ID3 algorithm in decision tree learning?

9. Write down the steps of constructing a decision tree using the ID3 algorithm

10. What role does entropy play in the ID3 algorithm?

11. How does ID3 determine the best attribute for splitting the dataset at each node?

12. What is information gain, and how is it used in the ID3 algorithm?

13. Why does the ID3 algorithm prefer attributes with the highest information gain?

14. How does the ID3 algorithm handle continuous attributes?

15. What are the potential drawbacks of using the ID3 algorithm in large datasets?

16. How does the ID3 algorithm handle missing or incomplete data?

17. Can the ID3 algorithm handle multi-class classification problems? How?

18. What is the stopping condition for the ID3 algorithm when building a decision tree?

Problem Set: Local Search

Course: CSE422 Artificial Intelligence

Problem Setups

1. For six cities, the matrix is given by:

[[ 0 39 65 53 56 41] [39 0 35 36 32 36]

[65 35 0 80 28 56]

[53 36 80 0 40 63]

[56 32 28 40 0 46]

[41 36 56 63 46 0]]

I would like to visit all cities, traveling the minimum distance.

1 7 72

2 16 68

3 12 90

4 7 54

5 16 73

6 3 44

7 16 64

8 4 38

9 4 18

10 19 94

3. Graph Description:

● Vertices: 7 vertices named A, B, C, D, E, F, G.

● Edges: Connections between the vertices are as follows:

○ A is connected to B, C, and D.

○ B is connected to A, C, E, and F.

○ C is connected to A, B, and G.

○ D is connected to A, E, and G.

○ E is connected to B, D, F.

○ F is connected to B, E, G. ○ G is connected to C, D, F.

Goal: The goal is to color the graph using the minimum number of colors such that no two adjacent vertices share the same color.

4. Graph Description:

● Vertices: 8 vertices named V1, V2, V3, V4, V5, V6, V7, V8.

● Edges:

○ V1 connected to V2, V3, V4

○ V2 connected to V3, V5

○ V3 connected to V4, V6 ○ V4 connected to V7

○ V5 connected to V6, V8

○ V6 connected to V7, V8

○ V7 connected to V8

Objective: Divide the vertices into two groups such that the number of edges between the two groups is maximized.

5. Problem Description:

● Assets: There are 5 different assets available for investment, each with its own expected return.

● Budget: The total amount available for investment is $50,000.

Asset Details:

● Asset 1: Expected return = 6%

● Asset 2: Expected return = 4%

● Asset 3: Expected return = 8%

● Asset 4: Expected return = 3%

● Asset 5: Expected return = 7%

Constraints:

● Investment Limits: No single asset should contain more than 40% of the total investment.

● Diversification: At least 3 different assets must be included in the portfolio. Objective: Maximize the expected return of the portfolio while adhering to the investment limits and diversification requirements.

6. Problem Description:

● Jobs: There are 10 jobs to be scheduled, each with different processing times.

● Machines: There are 3 machines available to process these jobs.

● Processing Times: Each job has a specific processing time, which is the same on any machine.

Job Details:

● Job 1: Processing time = 4 units ● Job 2: Processing time = 1 unit

● Job 3: Processing time = 8 units

● Job 4: Processing time = 5 units

● Job 5: Processing time = 3 units

● Job 6: Processing time = 6 units

● Job 7: Processing time = 2 units

● Job 8: Processing time = 7 units

● Job 9: Processing time = 9 units

● Job 10: Processing time = 3 units

Objective: Minimize the total time (makespan) to complete all jobs, where makespan is the time at which the last job finishes.

Questions:

For the each of the above problem setups:

b. Using Hill Climbing algorithm up to two iterations find the optimal solution. Using the idea of the evaluation function for this problem, explain the problems with the Hill-Climbing algorithm.

c. Using the problem scenario, explain how First-choice hill-climbing, Stochastic hill climbing and random restart hill climbing algorithm solves the issues with the Hill-Climbing algorithm.

d. Let𝑇(𝑘)𝑇 == 𝑇 1000 α𝑘, α = . 5 and the change of temperature at each iteration be described by

using, simulated annealing up to 3 iterations, find the optimal solution.

Explain the significance of the change of temperature in simulated annealing using this problem as an example. What will happen if the temperature is increasing at each iteration of simulated annealing.

e. Using the Genetic algorithm up to 1 iteration, find the optimal solution.

f. What will happen if all the chromosomes in the initial population are the same? Explain why mutation is helpful in finding a better solution. Use the problem scenario as an example.
