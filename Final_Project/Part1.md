# Outline

I self reported data regarding my weight loss efforts and some other variables during two periods of my life:
1. The fall and winter of 2016-2017
2. The spring and summer of 2019

Both of these efforts were successful, but had differing characteristics:
- Period 1 was much more strict about tracking my calories, less focused on routine exercise.
- Period 2 was more lax on calorie counting (I didn't use a tracking app) but had a much more strict exercise schedule. It also collected a lot more variables, such as the amount of sleep I got, the weather, etc.

By comparing these two periods, I want to convince the audience that a strict calorie counting using a tool (like MyFitnessPal, etc.) as well as a strict exercise routine will yield the best, most predictable weight loss results. In general, Period 1 demonstrates why tracking app are useful, and period 2 demonstrates the importance of frequent exercise. I also want to show particular habits about myself (days in which I tended to eat more, getting enough sleep, etc.) that might reveal themselves as something to be aware of or something to control when trying to lose weight, which can be achieved using the additional variables I collected in period 2. The overall story should contrast to the typical weight loss narrative: most of them fail. The goal is for it to be obvious that the specifics of my routine are what allowed it to be successful, and people might want to emulate it if they struggle to lose weight.

*The Story Arc*

***Setup***: Most weight loss efforts fail.

***Conflict***: My data shows two cases that were successful. What can the data reveal about why my efforts succeeded?

***Resolution***: A strict exercise routine and a tracking app to keep yourself honest and focused had a positive impact. (Controlling other habits like sleep, etc. support this as well.)

***Call to Action***: If you want to lose weight, tracking apps and a strict exercise routine will improve your results.

The story begins by presenting the audience with something they already know: most weight loss efforts fail. What if we could use data to show why some cases are successful? A quick visual summary of both of my datasets shows something clear: I was able to lose weight. Now the audience should be intrigued as to what allowed me to succeed. We can then delve into an analysis. 

Period 1 used a tracking app, and period 2 did not. How did period 1 benefit? A trend that I have already confirmed while exploring my data is that the differences between my actual and predicted weight for period 1 are smaller than period 2. In other words, a tracking app keeps me more honest about how many calories I can consume, making my weight loss more predictable.

We can also compare the amount of exercise between periods and see that period 2 has much more exercise, delivered more consistently. The total weightloss in period 2 was also higher. At least for me, more exercise had a benefit on my weight loss. In both periods, I had similar motivations and was in a similar environment, so differences aside from these methods were controlled for to the best of my ability. Based on that, we can conclude that two large impacts on my weight loss were the use of tracking apps, and a strict exercise routine.

Other habits can also be examined as well (analysis pending). For example, how much did sleep affect my calorie intake the next day? Being tired, for example, might make me grumpy and want to eat more to feel better. How much did exercise affect my self-reported mood? Do I feel better on days where I exercise? Do I eat more on holidays, at social events, or whenever I see my SO? If you are trying to lose weight, seeing these trends might help you understand some habits you might want to consider controlling.

# Sketches
Below are sketches for some of my planned visualizations:

![Build Intrigue, Explore Data](https://jhumes.github.io/Humes-Portfolio/Final_Project/Sketches/Sketches1.jpg)

![Call to Action](https://jhumes.github.io/Humes-Portfolio/Final_Project/Sketches/Sketches2.jpg)

# Data
My data can be downloaded as an excel workbook here: [Weight_Loss.xlsx](https://jhumes.github.io/Humes-Portfolio/Final_Project/Weight_Loss.xlsx)

The workbook contains two sheets: the 2016-2017 data, and the 2019 data. For the data sheets, each row represents a unique day with values for each attribute. In general, each day has the date and my measured weight that morning, followed by a running average to smooth out the weight trend, my calories consumed, calories burned, my expected weight loss as a result of calories burned, and a predicted trend generated from the expected weight loss. The 2019 data has a few more variables, such as dedicated columns for showing my actual and predicted changes in weight, and some categorical variables such as whether it rained, whether I attended class, drank alcohol, or saw my SO, for example. It also measures my hours of sleep the previous night, a daily rating of my mood on a scale of 1 to 5, with 5 being better, and a scale of how tired I felt from 1 to 5, with 5 being more tired.

Collection specifications:
- Period 1 tracked calories consumed using the MyFitnessPal app, period 2 used my best judgement.
- My weight was collected at roughly the same time every morning, immediately after waking up and using the restroom, before eating or drinking anything.
- Miles ran was tracked using google maps.
- Calories burned per mile was calculated by multiplying that day's weight in pounds by .75 (a general rule of thumb).
- Hours of sleep the previous night was recorded each morning after waking up.
- All other variables, such as the categorical ones and the variables tracking mood and tiredness were based on my subjective input and weren't tracked via any technology.

In terms of how my data will be used, the meat of my visualization will be comparing the trend of my actual weight loss to the trend of my predicted weight. These comparisons allow for key insights as to how the differences in methodology affetced my weight loss. The categorical variables are mostly used to subset my data to ask interesting questions about my habits. For example, I could ask "on days that I considered a cheat day (cheat = 1), did I actually tend to consume more calories (avg. calories consumed) than non-cheat days (cheat = 0)?" Other numeric columns, such as my hours of sleep, or my mood rating, will usually be represented by some sort of summary statistic like an average when subsetted by one of the categorical variables, such as day of the week. I may update the data with new calculated columns as the project advances.

# Method and Medium

The final project will be presented in Shorthand.

It will have the general structure:

First, an introduction describing that most weight loss efforts fail, backed up by some statistics. Then, my data will be introduced with one simple visualization that reveals my efforts as successful. Then, a section exploring some of the data to build interest, looking at my habits that I spoke about in the Outline section. All of these explorations would follow of format of visualization followed by explanation/context, going through all of the interesting variables and trends and explaining how it relates to my weight loss and why being aware of it or controlling it might help people looking to lose weight. A final section will use the visualization of the actual vs. predicted trends for my weight to drive home the call to action that tracking apps and a strict exercise routine can have a positive impact on weight loss.

[Return to Portfolio](https://jhumes.github.io/Humes-Portfolio/)
