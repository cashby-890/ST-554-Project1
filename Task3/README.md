Each group member should provide feedback on the other group members’ work. Be detailed and specific where possible. The quality of this feedback can play a part in your grade.

You can provide feedback to your group members in many different ways (live in a meeting, offline, or however else you devise) but the feedback must be documented here! 

Please replace “Feedback giver #x” with a group member’s name below and add feedback as a bulleted list below. Note: There is a pencil icon on the top right of the README file (when you are viewing the README.md file) that allows you to edit.

- Feedback from Franklin Zhou
  + The `getCurrentMSE()` function may have some issue. Based on the instruction, this function should work by feeding with the entire `X` and `y` from data set rather than a sub data set that only contains first `day+1` rows. Simply use `getCurrentMSE(X = x_cols, y = y_col, day = n)` to call the function. I would suggest to do subsetting inside the function. 
  + As to the iteration, the instruction says "iterate from the day (here day 250, but this leaves it up to the user to decide) to the final day in the data set minus 1". Should the `for i in range(day, len(X))` be `for i in range(day, len(X)-1)`?
  + I would suggest to add an if else logic to determine if the user's input day is out of support and throw a warning message maybe. For example, what if user input 999 as day value? Though this is not included in the instruction, but in real life, you never know what would user do...
  + Overall, Max did a great job!!


- Feedback from Cody Ashby
  + Everything looks pretty great so far. However, when subsetting the data in your `getCurrentMSE()` function, I think you should reindex your training and testing set as follows for both your `X` and `y`: `X_train = X.iloc[:day]` and `X_test = X.iloc[day+1]`. Running your function at the moment currently uses all but the last entry in the data set, which is not quite the goal in this cross-validation process.
  + I also think it would be a good idea to include a derivation on calculating the MSE for a linear regression model in a markdown cell so that the target audience (i.e. people that only know the basics of statistics and/or programming) won't get to thrown off with all the mathematical jargon.
  + Other than that and polishing already typed narratives a little, I think you're all set!
