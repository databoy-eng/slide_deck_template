# Ford GoBike System Data slide_deck_template
This project is divided into two major parts. In the first part, you will conduct an exploratory data analysis on a dataset of your choosing. You will use Python data science and data visualization libraries to explore the dataset’s variables and understand the data’s structure, oddities, patterns and relationships. The analysis in this part should be structured, going from simple univariate relationships up through multivariate relationships, but it does not need to be clean or perfect. There is no one single answer that needs to come out of a given dataset. This part of the project is your opportunity to ask questions of the data and make your own discoveries. It’s important to keep in mind that sometimes exploration can lead to dead ends, and that it can take multiple steps to dig down to what you’re truly looking for. Be patient with your steps, document your work carefully, and be thorough in the perspective that you choose to take with your dataset.

In the second part, you will take your main findings from your exploration and convey them to others through an explanatory analysis. To this end, you will create a slide deck that leverages polished, explanatory visualizations to communicate your results. This part of the project should make heavy use of the first part of the project. Select one or two major paths in your exploration, choose relevant visualizations along that path, and then polish them to construct a story for your readers to understand what you found.

Step 1.2: Explore Your Data
It’s time to get to the interesting bits. Explore your data and document your findings in a report. The report should briefly introduce the dataset, then systematically walk through the points of exploration that you conducted. You should have headers and text that organize your thoughts and findings. Visualizations in this part of the project need not be completely polished: this is just your own exploration at this point. However, you should still make sure that you adhere to principles of using appropriate plot types and encodings so that accurate conclusions can be drawn, and that you have enough comments and labeling so that when you return to your work, you can quickly grasp your analysis steps.

If you use a Jupyter Notebook for this step of the project, don’t forget to export the notebook as an html file for the project submission.

Step 2.1: Document your Story
At the end of your exploration, you probably have a bunch of things that you’ve discovered. Now it’s time to organize your findings and select a story that you will convey to others. In your readme document, you should summarize your main findings and reflect on the steps you took in your data exploration. You should also lay out the key insights that you want to convey in your explanatory report as well as any changes to visualizations, or note new visualizations that will be created to bridge between your insights.

Step 2.2: Create your Slide Deck
Follow the plans you laid out in the previous step and create a slide deck with explanatory data visualizations to tell a story about the data you explored. You can start with code that you used in your exploration, but you should make sure that the code is revised so that your plots are polished. Make sure that you also pay attention to aspects of design integrity in your revisions.

Step 2.3: (Optional) Get Feedback
Though not required, it is highly recommended that you try to get feedback from at least one person before you submit your project. By sharing your work with others, you can get input from a different perspective that catches things that you may have originally missed. Share your slide deck with someone in person and have them provide live feedback on what they get from your slide deck. Alternatively, you can also share your work with your fellow students. Post a message in a student community channel for this project with a link to your project and ask for feedback. Be sure to keep an eye out for others who are also seeking feedback and return the favor!

You might need to ask specific questions to prompt your reader. The following questions might be good starters; be sure to follow up or come up with your own questions:

What do you notice about each visualization?
What questions do you have about the data?
What relationships do you notice?
What do you think is the main takeaway from the slide deck?
Is there anything that you don’t understand from the plots?
If you get feedback from others, then add their feedback to your readme document. Note what changes you make to your slide deck and designs based on that feedback. You can also include feedback from your reviewer as part of this revision process.

## Dataset

> The data consists of information regarding 3.27 billion bike hiring, including
age, timeframe, gender, station, and others. The dataset can be found in Ford GoBike website. Dataset: (https://s3.amazonaws.com/fordgobike-data/index.html). The data consisted of 16 different variables such as age, gender, weekday, time and others. It contains 3.27 billion rides. Ages in dataset from 18 to 56 takes 95% of the users in dataset. There were users more than 100 years old. So, we can remove users more than 60 years old as a cleaning and tidy up. We also generated new fields such as age group in order to make grouping and analyze the date by using groups. Ford GoBike extended the service to San Francisco, Oakland and San Jose. However, regarding complexity of traffic, we decided to focus on the San Fancisco area.


## Summary of Findings

> There were 3.27 billion rides and 20 to 40 years old people took the more than 70% of bike rides. Among those, 30 to 40 years old people's rides account almost 40% of all bike rides. Males demonstrate 76% of all bike rides, in turn females are viewes with taken 22% of them. The data illustrates users use the service on weekdays moreso than on weekends. Data shows 8am and 5pm as the peak hours for this service. Illustrating the majority of users utilize during the commuting hours, in addition, during lunch hours. As well, subscribers rides as most significant decreasing toward the winter session than customers. Subscribers' average trip duration around 11 minutes. Conversely, customers' average trip duration of 28 minutes. 80% of the rides are from subscribers and it illustrating use of service during commute hours. Subscribers and customers trip distance were comparable, which is moderately more than one mile. Subscribers' most frequently used timing is around 7 ~ 9am and 4 ~ 6pm, which is a commute time. In the contrary, Customers' most frequently used timing are weekend 12pm ~ 4pm and weekday 5pm ~ 6pm. Customers tend to use this service during weekend for leisure and after work. 40 to 50 year old users tend to use the service signifantly above other users.


## Key Insights for Presentation

> For the presentation, we focused on the impact of age, timeframe, weekday, age group of bike hiring data. We started by introducing the age distrubition, monthly bike hiring trend, followed by age group distribution, then plot the weekday, timeframe with age data.  We implemented different color palettes for each variables for clarity.
