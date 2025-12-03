# Assignment 6 Part 1 - Writeup

**Name:** _______________  
**Date:** _______________

---

## Part 1: Understanding Your Model

### Question 1: R² Score Interpretation
What does the R² score tell you about your model? What does it mean if R² is close to 1? What if it's close to 0?

**YOUR ANSWER:**
It tells us how close the variation of our test scores are. We want R2 to be as close to 1 as possible. When it is closer to 1, there is a strong correlation between studying and test scores.



---

### Question 2: Mean Squared Error (MSE)
What does the MSE (Mean Squared Error) mean in plain English? Why do you think we square the errors instead of just taking the average of the errors?

**YOUR ANSWER:**

MSE is the difference between a predicted value and the plotted value that is on the graph. This can be used to see how accurate a best fit line is. Squaring the errors would better show the distant between the two points.


---

### Question 3: Model Reliability
Would you trust this model to predict a score for a student who studied 10 hours? Why or why not? Consider:
- What's the maximum hours in your dataset?
- What happens when you make predictions outside the range of your training data?

**YOUR ANSWER:**

I personally wouldn't trust this model to predict a score for a student who studied for 10 hours since the max number of studying is 9.5. Since we don't have data for 10 hours of studying there might be some affecting factors. Studying for so long might not show as much improvement towards the end.


---

## Part 2: Data Analysis

### Question 4: Relationship Description
Looking at your scatter plot, describe the relationship between hours studied and test scores. Is it:
- Strong or weak?
- Linear or non-linear?
- Positive or negative?

**YOUR ANSWER:**

The relationship between hours studied and test scores is mostly strong. You can make the scatter plot linear with the best fit line. It is a positive relationship.


---

### Question 5: Real-World Limitations
What are some real-world factors that could affect test scores that this model doesn't account for? List at least 3 factors.

**YOUR ANSWER:**
1. Accessiblity to online resources and textbooks
2. Environment
3. Difficulty of class (Honors, AP)


---

## Part 3: Code Reflection

### Question 6: Train/Test Split
Why do we split our data into training and testing sets? What would happen if we trained and tested on the same data?

**YOUR ANSWER:**

The reason that we split our data into training and testing sets is to check if the model is able to create a line of best fit and estimate a slope. If we trained and tested on the same data then the model would be correct but also a little unreliable since it has all of our data.   


---

### Question 7: Most Challenging Part
What was the most challenging part of this assignment for you? How did you overcome it (or what help do you still need)?

**YOUR ANSWER:**

In my opinion, finding out how to work the new funcitons was probably the hardest part. I had to do research and use the help of my friends to figure out how to do some of my code. Other than that, I had a good time working on this assignment. 


---

## Part 4: Extending Your Learning

### Question 8: Future Applications
Describe one real-world problem you could solve with linear regression. What would be your:
- **Feature (X):** 
- **Target (Y):** 
- **Why this relationship might be linear:**

**YOUR ANSWER:**

X -> Location and Size of a house
Y -> House price
This is linear because house prices tend to have a linear relationship depending on the location and size of a house.


---

## Grading Checklist (for your reference)

Before submitting, make sure you have:
- [ ] Completed all functions in `a6_part1.py`
- [ ] Generated and saved `scatter_plot.png`
- [ ] Generated and saved `predictions_plot.png`
- [ ] Answered all questions in this writeup with thoughtful responses
- [ ] Pushed all files to GitHub (code, plots, and this writeup)

---

## Optional: Extra Credit (+2 points)

If you want to challenge yourself, modify your code to:
1. Try different train/test split ratios (60/40, 70/30, 90/10)
2. Record the R² score for each split
3. Explain below which split ratio worked best and why you think that is

**YOUR ANSWER:**
