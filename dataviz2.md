# Homepage

[back to my homepage](/README.md)



# The original data visualization
While browsing through the CMU website, I found this particular data visualization that intersted me. The visualization is the positive COVID cases related to CMU faculties and students, and including those on campus and off campus. The data are presented both in by week format and in by month format. The charts and links are shown below:

![Running Cases by Week](https://user-images.githubusercontent.com/90215938/134103475-2e70b5cb-7ee2-4f1d-b426-4127807df997.png)
![Running Cases by Month](https://user-images.githubusercontent.com/90215938/134103496-433b559a-39c2-452b-bcdf-4e20490e65ad.png)

Source: CMU COVID-19 Dashboard, https://www.cmu.edu/coronavirus/health-and-wellness/dashboard.html, https://docs.google.com/spreadsheets/d/1AakaSeEoyJ_jRX7drZDkQNx10UC6hBtNQJhEaJ8BuXs/edit#gid=1592617220

I particularly chose the data for three reasons:

First, the data presented are important and are concerned by most people. Since the development of the COVID-19, it has been the hotest issue among all people. Especially for students and faculties who are unable to stay quarantine because of the coursework, we can interested in receiving updated and clear information about the development of COVID-19 cases on campus. As a result, improving the quality of the data visualization of COVID cases on CMU website is important.

Second, the visualization has pleanty of rooms to improve. As discussed in my Stephen Few's Data Visualization Effectiveness Profile spreadsheet, the colors, the labels, the type of visualization have rooms to improve. The visualization chart contains too much information for readers to absorb, and unclear labels create boundaries for audience to catch up with the information effectively and efficiently.

Third, the data is relatively easy to access. Luckily, CMU provides a Google spreadsheet for us to dig into the original data, and set up a friendly environment for further improvements.

# Wireframing
As discussed before, I would like to reduce the colors, change the type of visualization for the by month graph, and add clear labels to the graph. As a result, I have done my first wireframing visualization chart using pens:

![wireframe1](https://user-images.githubusercontent.com/90215938/134106683-e26d4020-e25b-4632-b975-fa1de4ab27b2.jpg)
![wireframe2](https://user-images.githubusercontent.com/90215938/134106733-17fbac5d-3889-4901-ad7c-12d1ce342a89.jpg)

For the by week running positive cases chart, I maintained the original type and layouts of the chart. Bar chart for small numbers of periods of time is effective to show the proportions of each category. There are a few things that I have changed: 

First, I changed the color and reordered the proportions in the bar. I put positive cases of on campus students and faculties in the top of the bar to emphasize and catch the audience's attetion in the first glance, because I believe our target audience would like to know the running positive cases on campus the most. I also used bright colors to emphasize the importance of the running positive cases on campus for readers, and used grey colors to show the cases that are off campus in contrast.

Second, I added labels to the bars and explanatory legends on the side of the bars. I also deleted redundant information such as the years of the bars, since I believe audience would definitely know the current year period of the weekly data. The reason why I added numbers to the bars is that I think it is important to let the audience know the exact number of positive cases in CMU community by showing them directly the numbers and how they are changing over time. 

For the by month running positive cases chart, I changed the type of the data visualization and recreate a new one.

First, I changed bar chart into line charts. Since there are so many bars in the original by month bar chart, I changed the type of visualization into line chart. Stacked line chart can also show the trend of total positive numbers and different proportions of the positive cases without creating a complex and confusing color effect. Now we can clearly see how different proportions of positive cases are spreading among faculties and student and how they are changing over time.

Second, in order to align with the previous by week bar chart, I used the same color and notation to emphasize the importance of existing positive cases on campus. Grey colors are also used in positive cases off campus to be compared with the bright color of positive cases on campus.

# Testing

In this part, I invited two friends of mine to take a look at my wireframing visualization and to give me useful insights and suggestions.

Here are the questions and their answers:

- What do you see and capture at first sight? What is this chart about?

Answer1: It is the positive COVID cases in CMU, but I find it confusing in the sense that you do not specify CMU or COVID in either your title or your label.

Answer2: It is how the number of COVID cases are changing over time.

- What do you think is the target audience?

>Answer1: It should be Students and Faculties.

>Answer2: It should be people inside the CMU community.

- Are there any places you find awkward or confusing?

>Answer1: The title is not clear enough, and you should change it.

>Answer2: 
