# Philadelphia Covid Trends
This project uses the covid testing data provided by City of Philadelphia through [OpendataPhilly](https://www.opendataphilly.org/dataset/covid-cases).
Charting for this project uses the image charts API by [image-charts.com](https://www.image-charts.com)

# Background
Over the past 2 years covid has continued to be an issue for Philadelphia and people around the world and as such people have been testing and perhaps even overtesting. This data chart shows both the number of positive and negative tests that occured on one particular day and puts it into chart form for better understanding. When looking at monthly data you can see how many positive and negative tests occured each month and how it compares to the total number of tests, you can also see the total number of positive tests for each month, and you can see a side by side bar graph between positive and negative tests without the total number tests to give a better zoom making it easier to see the positive tests compared to negative tests.

# API Usage
The data is collected from the City of Philadelphia via OpendataPhilly in CSV format which is then interpreted in javascript to format properly for both the data charts and to put it in a readable format for users. This dataset is updated every monday to keep up to date data and is automatically processed without needing new code.
Image-charts.com is used to create the charts used by this program to using a interpreted image url to a javascript file. The data from OpendataPhilly is automatically processed into Image-charts url format requiring no interaction by the user besides hitting the go button.
