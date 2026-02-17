Each group member should provide feedback on the other group members’ work. Be detailed and specific where possible. The quality of this feedback can play a part in your grade.

You can provide feedback to your group members in many different ways (live in a meeting, offline, or however else you devise) but the feedback must be documented here! 

Please replace “Feedback giver #x” with a group member’s name below and add feedback as a bulleted list below. Note: There is a pencil icon on the top right of the README file (when you are viewing the README.md file) that allows you to edit.

- Feedback from Franklin Zhou
  + The `getCurrentMSE()` function may have some issue. Based on the requirement, this function should work by feeding with the entire `X` and `y` from data set rather than a sub data set that only contains first `day+1` rows. Simply use `getCurrentMSE(X = x_cols, y = y_col, day = n)` to call the function. I would suggest to do subsetting inside the function. 
  + `return((y_test - y_hat)**2)` returns the sum of squared errors, not mean squared error.
  + In the iteration, the instruction says "iterate from the day (here day 250, but this leaves it up to the user to decide) to the final day in the data set minus 1". Should the `for i in range(day, len(X))` be `for i in range(day, len(X)-1)`?
  + I would suggest to add an if else logic to determine if the user's input day is out of support. For example, what if user input 999 as day value?
  + Overall, Max did a great job!!


- Feedback giver #2
  + item
