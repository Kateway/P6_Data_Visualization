# Titanic Survival Status Visulization
## Summary
The titanic dataset is downloaded from Kaggle.  The Titanic ship sank on April 15, 1912 after colliding with an iceberg.  This tragedy killed 1502 out of 2224 passengers.  Not having enough life boats is one of the reasons that so many life were lost.

The objective of this project is to show the survival status differences across gender of the passenger, so that readers can get a clear view to compare it.

## Chart Selection
A bar chart is plotted to show the differences of survival status across gender. It is easy for comparison and understanding. Stacked bar chart is used after incorporating feedbacks.

A column called "Count" was created for plotting.

The titanic dataset is a tiny dataset, therefore, no cleaning is needed.

## Visual Encoding
x axis: Passenger gender y axis: Percentage color hue: survived or perished

## Tool Selection
dimple.js is selected to implement the visual encoding. It is easy to use and creates very nice charts.

## Feedbacks
Initially, the bar chart shows the different survival rates among gender.  However, it is not very clear.  I got several feedbacks to improve it after speaking to at least three persons.
1. Use percentage as y axis
2. Add both survived and perished bars (use stacked bar charts)
2. Add legend

## Resources
1. Udacity data visulization class and forum
2. dimple.js documentation
3. Titanic dataset on Kaggle https://www.kaggle.com/c/titanic
