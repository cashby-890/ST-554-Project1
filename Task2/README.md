Each group member should provide feedback on the other group members’ work. Be detailed and specific where possible. The quality of this feedback can play a part in your grade.

You can provide feedback to your group members in many different ways (live in a meeting, offline, or however else you devise) but the feedback must be documented here! 

Please replace “Feedback giver #x” with a group member’s name below and add feedback as a bulleted list below. Note: There is a pencil icon on the top right of the README file (when you are viewing the README.md file) that allows you to edit.

- Feedback From Franklin Zhou
  + May need the interpretation to the histograms, scatterplots and correlation matrix. 
  + From the histograms, we see that  `C6H6(GT)` is skewed while some of the other variables is normally distributed. Maybe you need to do transformation to `C6H6(GT)` variable.
  + The instructions require numeric summaries of `C6H6(GT)` at "different levels/combinations of other variables". While you have done this for time variables (date/year), you should also consider creating bins or levels for weather variables (like Temperature or Relative Humidity) and summarizing `C6H6(GT)` across those levels.
  + What's the meaning of putting covariance matrix here?
  + The instruction says "You should look at relationships over time and also ignoring time." You should include scatterplots showing `C6H6(GT)` on the y-axis and different sensor or weather variables on the x-axis to visualize these relationships with and without the context of time.
  + I would recommend deepen the narrative part to explain what the outputs mean.


- Feedback from Max Campbell
  + Since this is the EDA portion of the data, I think it would be helpful to go as far as to establish what each individual column represents at the beginning. You do have a general summary, but right now I don't think a reader of the target audience would understand what `PT08.S4(NO2)` represents just by reading it. 
  + I see that you drop the `(GT)` columns, but I'm not quite sure why. It would be helpful if you explained that when you drop the columns.
  + In order to get all those warnings to go away when you convert the objects to DateTime objects, you should convert the column in the full dataset to a DateTime object when you first read it in. I had a similar issue in my code and was able to resolve it that way.
  + I understand that this is a rough draft so you are probably aware of this, but interpretations for all of the EDA you are performing will be necessary before this is ready to submit.
  + This is a solid start! I'm aware that you had time constraints, so let me know if you need any help in getting this done next week if time becomes an issue.

