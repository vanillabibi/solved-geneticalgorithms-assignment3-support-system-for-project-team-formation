Download Link: https://assignmentchef.com/product/solved-geneticalgorithms-assignment3-support-system-for-project-team-formation
<br>
The problem of optimal team formation is domestic to many areas of work organization including education, sport, and business. It is beyond manual implementation to build near optimal teams as soon as the pool of available personnel grows into several tens. The selection process itself is usually well defined for each team we construct the criteria relating to the required properties of the team members. Because these properties can be arbitrarily combined in the personnel, the objective function becomes self-conflicting. This aggravates the team formation and calls for specialized software support.

We use quantities values to describe the employees’ capabilities like technical expertise and also to describe the budget limits needed to format a team

The problem is to estimate the level of risk involved in a software engineering project. For the sake of simplicity, we will arrive at our conclusion based on two inputs: project funding and technical experience for the team members.




Suppose our inputs are project_funding and team_experience_level. We can get the fuzzy values for these crisp values by using the membership functions of the appropriate sets.




The sets defined for <strong>project_funding</strong> are very low (0,0,10,30), low (10,30,40,60),  medium (40,60,70,90), high (70,90,100,100).




The sets defined for <strong>team_experience_level</strong> are beginner (0,15,30), intermediate (15,30,45), expert (30,60,60).




The set defined for the <strong>risk</strong> is high (0,25,50), normal (25,50,75),  low (50,100,100).




<strong> </strong>

<h1>The Rules</h1>

Now that we have the fuzzy values and we can use the fuzzy rules to arrive at the final fuzzy value. The rules are as follows:

<ol>

 <li>If <em>project_funding</em> is <strong>high</strong> or team_experience_level is <strong>expert</strong> then risk is <strong>low</strong>.</li>

 <li>If <em>project_funding</em> is <strong>medium</strong> and team_experience_level is <strong>intermediate</strong> or team_experience_level is <strong>beginner </strong>then risk is <strong>normal</strong>.</li>

 <li>If <em>project_funding</em> is <strong>very</strong> <strong>low</strong> then risk is <strong>high</strong>.</li>

 <li>If <em>project_funding</em> is <strong>low</strong> and team_experience_level is <strong>beginner</strong> then risk is <strong>high</strong>.</li>

</ol>

<strong>Input: </strong>

<ul>

 <li>First line represents number of input variables = 2</li>

 <li>Second line gives a Variable Name and its crisp input to fuzzify it later (e.g.</li>

</ul>

project funding 50, experience level 40).

<strong> </strong>

<strong>Output: </strong>

<ul>

 <li>Fuzzifying the inputs</li>

 <li>Inference of rules</li>

 <li>Defuzzification output</li>

</ul>







<strong><u>Test Case</u> </strong>

<strong> </strong>

<strong><u>Input:</u> </strong>

<strong> </strong>

<strong>Variables: 2 Project Fund: 50   Experience Level: 40 </strong>

<strong> </strong>

<strong><u>Output:</u> </strong>

<strong> </strong>

<h1>Predicted Value (Risk) = <u>66.6</u> Risk will be <u>Normal</u></h1>

<strong> </strong>

<strong>Assignment submission notes: </strong>




<ul>

 <li>The maximum number of students in a team is 3 and the minimum is 2.</li>

</ul>




<ul>

 <li>The deadline is 31/12/2020 and no late submission is allowed.</li>

</ul>




<ul>

 <li>Please submit one compressed folder. The folder name should follow this structure: ID1_ID2_ID3 _GROUPNAME</li>

</ul>




<ul>

 <li>Cheating students will take negative grades and no excuses will be accepted. If you have any problems during the submission, contact your TA but don’t, under any circumstances, give your code to or take the code from your friends.</li>

</ul>


