# Amazon Vine Analysis
In this challenge, we take a look at a category of items sold on Amazon. We specifically look at users that are part of the "Vine" review program. Through analysis, I determine if the category I selected, wrist watches, has biased reviews by those who are a part of the "Vine" program.

## Results
From the analysis that was run, I determined several things:

First, I loaded the data into a usable table:

![](Images/vine_table.png)

Using code from the images below, I was able to filter all Vine reviewers' reviews and get a count, 5-star review count, and 5-star reviews percentage.

![](Images/get_vine.png)

![](Images/vine_reviews.png)

- There were 47 reviews left by Vine reviewers.
- Out of those, there were 15 5-star reviews.
- Of all reviews left by Vine reviewers, 31.91% were 5-star reviews.

---
I then collected the same information for non-vine reviews.

![](Images/get_not_vine.png)

![](Images/not_vine_reviews.png)

- There were 8362 reviews left by independent reviewers.
- Out of those, there were 4332 5-star reviews.
- Of all reviews left by independent reviewers, 51.81% were 5-star reviews.
