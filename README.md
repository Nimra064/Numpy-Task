# Python Library Numpy
## Task 1
1. Data file is recipes.csv. link : https://github.com/Nimra064/Numpy-Task/blob/master/NumpyTask1/recipes.csv  <br>
2. Attached with jupyter notebook <br>
3. All of Alize’s recipes call for milk, eggs, sugar, flour, and butter. For example, her cupcake recipe calls for: <br>
Flour Sugar Eggs Milk Butter 2 cups 0.75 cups 2 eggs 1 cups 0.5 cups Create a NumPy array that represents this data. Each element should be a number (i.e., 2 for “2 cups”). Save this array as cupcakes.<br>
3. Alize’s assistant has compiled all of her recipes into a csv (comma-separated variable) file called recipes.csv. Load this file into a variable called recipes.<br>
Display recipes using print. Display recipes using print.<br>
4. Each row represents a different recipe. Each column represents a different ingredient.<br>
5. Recipe Cups of Flour Cups of Sugar Eggs Cups of Milk Cups of Butter<br>

Cupcakes … … … … … <br>

Pancake … … … … … <br>

Cookie … … … … … <br>

Bread … … … … … <br>
6. The 3rd column represents the number of eggs that each recipe needs. <br>
7. Which recipes require exactly 1 egg? Use a logical statement to get True or False for each value of eggs. <br>
8. Alize is going to make 2 batches of cupcakes (1st row) and 1 batch of cookies (3rd row). <br>
9. Get the number of ingredients for a double batch of cupcakes by using multiplication on cupcakes. Save your new variable to double_batch. <br>
10. Create a new variable called grocery_list by adding cookies and double_batch. <br>


## Task 3
## CrunchieMunchies
You work in marketing for a food company myCorps, which is developing a new kind of tasty, wholesome cereal called CrunchieMunchies.You want to demonstrate to consumers how healthy your cereal is in comparison to other leading brands, so you’ve dug up nutritional data on several different competitors. Your task is to use NumPy statistical calculations to analyze this data and prove that your CrunchieMunchies is the healthiest choice for consumers.<br>

1.Look over the cereal.csv file. link here : https://github.com/Nimra064/Numpy-Task/blob/master/NumpyTask2/cereal.csv  This file contains the reported calorie amounts for different cereal brands. Load the data from the file and save it as calorie_stats.<br>
3. There are 60 calories per serving of CrunchieMunchies. How much higher is the average calorie count of your competition?Save the answer to the variable average_calories and print the variable to the terminal to see the answer. <br>
4. Does the average calorie count adequately reflect the distribution of the dataset? Let’s sort the data and see. Sort the data and save the result to the variable calorie_stats_sorted. Print the sorted data to the terminal. <br>
5. Do you see what I’m seeing? Looks like the majority of the cereals are higher than the mean. Let’s see if the median is a better representative of the dataset.
Calculate the median of the dataset and save your answer to median_calories. Print the median so you can see how it compares to the mean.<br>

6. While the median demonstrates that at least half of our values are over 100 calories, it would be more impressive to show that a significant portion of the competition has a higher calorie count that CrunchieMunchies. Calculate different percentiles and print them to the terminal until you find the lowest percentile that is greater than 60 calories. Save this value to the variable nth_percentile.<br>

7. .While the percentile shows us thatthe majority of the competition has a much higher calorie count, it’s an awkward concept to use in marketing materials.Instead, let’s calculate the percentage of cereals that have more than 60 calories per serving. Save your answer to the variable more_calories and print it to the terminal. <br>

8. While the percentile shows us thatthe majority of the competition has a much higher calorie count, it’s an awkward concept to use in marketing materials.Instead, let’s calculate the percentage of cereals that have more than 60 calories per serving. Save your answer to the variable more_calories and print it to the terminal. <br>

9. Wow! That’s a really high percentage. That’s going to be very useful when we promote CrunchieMunchies. But one question is, how much variation exists in the dataset? Can we make the generalization that most cereals have around 100 calories or is the spread even greater? Calculate the amount of variation by finding the standard deviation</em Save your answer to calorie_std and print to the terminal. How can we incorporate this value into our analysis? <br>

10. Write a short paragraph that sums up your findings and how you think this data could be used to myCorp’s advantage when marketing CrunchieMunchies.<br>
## Conclusion :
yes,CrunchieMunchies is the healthiest choice for consumers. Because, mean and average calories are greater than 100. Median is atleast half of the calories greater than 100. majority of calories greater than 100.

## Task 3
## Election Results
You’re part of an impartial research group that conducts phone surveys prior to local elections. During this election season, the group conducted a survey to determine how many people would vote for I_Khan vs. S_Sharif in the presidential election. Now that the election has occurred, your group wants to compare the survey responses to the actual results. Was your survey a good indicator? Let’s find out! <br> 
##Steps 
1. Import the Relevant Library like NumPy and matplotlib.<br>
2. There is a list given of the different survey responses.Calculate the number of people who answered ‘I_Khan’ and save the answer to the variable total_Khan.Print the variable to the terminal to see its value.<br>
3. Calculate the percentage of people in the survey who voted for I_Khan and save it to the variable percentage_I_Khan.
4. In the real election, 54% of the 10,000 town population voted for I_Khan. Your supervisors are concerned because this is a very different outcome than what the poll predicted. They want you to determine if there is something wrong with the poll or if given the sample size, it was an entirely reasonable result.

Generate a binomial distribution that takes the number of total survey responses, the actual success rate, and the size of the town’s population as its parameters. Then divide the distribution by the number of survey responses. Save your calculation to the variable possible_surveys. <br> 
5. By using matplotlib Plot a histogram of possible_surveys with a range of 0-1 and 20 bins. <br><img width="294" alt="Histogram" src="https://user-images.githubusercontent.com/71897920/232977540-89a07bb8-1005-4dbe-bbdb-8b98741d4fcd.png">
 <br>
6. As we saw, 47% of people we surveyed said they would vote for I_Khan, but 54% of people voted for I_Khan in the actual election.Calculate the percentage of surveys that could have an outcome of I_Khan receiving less than 50% of the vote and save it to the variable I_Khan_loss_surveys.Print the variable to the terminal.<br>
7. With this current poll, about 20% of the time a survey output would predict S_Sharif winning, even if I_Khan won the actual election.Your co-worker points out that your poll would be more accurate if it had more responders.Generate another binomial distribution, but this time, see what would happen if you had instead surveyed 7,000 people. Divide the distribution by the size of the survey and save your findings to large_survey.<br>
8. Now, recalculate the percentage of surveys that would have an outcome of I_Khan losing and save it to the variable I_Khan_loss_new, and print the value to the terminal.What do we notice about this new value? What advice would you give to your supervisors about predicting results from surveys? <br>
## Conclusion <br>
This indicate that percentage value of both survay approxmiate equal to each other to loss the vote







