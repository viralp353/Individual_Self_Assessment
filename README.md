# Individual_Self_Assessment
 
 
 In First Week,We started to pick topics for final week.We had a lot of topics just like wine_weather,Covid-19,Election prediction, Amazon price tracker,Twitter sentimental but We picked to Wine_weather as per team's decision by zoom metting & discussed in slack.We divided group into different task.Based on that  for me ,Wine'api was given by team. On Inital base,It was very frusruted to find wine api but Finally i gotGolbal wine score  by bunch of reserch.Golbal wine api has a some input parameter just like applleation,Wine_name,Wine_score,Region,Color,Country.We decided to pick as Usa country and Red&White as Color as per team's disccussion.Red & White Api converted into csv form.
 
 
 
 
 In Second Weeek,We would required to pick common link for weather data for future Analysis.We decided to go with appellation.We assumed that Weather would be same around 50 miles zipcodes.I tried to find all appellation manual.Based on that I found that,Napa's zip code has cover a lot of appellation of wine and as well as Sonoma's zip code has cover a lot of appellation.I found 8 applleation cover all wine data's appellation.Now One more challenge on second week that  How can we  connect Weather & Wine? .Me&my teammate 's Shawn worked continued on connect weather & Wine.We had 2 week between week-2&week-3 project segment.That'why We had lot of days to slove complex problem but we did it by a lot of failur.
 
 
 
 In Third Week,We had a data with clean.One of Teammate had alrerady set up machine learning with Aws server.Now We were need to find best model fit for data.I was also drive into machine learning to try to get high accuray.I contributed also tableu set up in third week.
 
 
In Fourth and final week for Project ,Our TA gave to us  one more challenge to add web app as part of Darshboad That'why We had a lot of frusruted. Because nobody had any type of exprience  for dump machine learning into flask app.Everybody tried to find way by watching video about dump machine learning dump into flask app.I was also drive into to find solution.Finally We got solution about it.I prepared also  tableau and ppt google side for presentations.




# Team Assessment:


For Project ,We had a powerfull team just like-Sonia , Val, Shawn, Neal,Meredith and me.We started to pick topics for final week.We decided to pick a Wine_weather for final project And also Soil data keep in mind.Because  of We need a storng base for project.We did split team into 3 different team's task just like-One team for Data Cleanning &Data Expolation, One Team for Machine Learning and One Team for Database,PPt,Presentations. 


Everybody did good job in project .Communicate through Slack. Everyone uploads data to their Github branch and create a pull request. One Teammate merges the data after everyone discuss the final plans.Each member of team had there own branch and makes at least 4 commits per week.

Everybody helped to each other whenever sometime stuck in problem.We did it by all team member.

# Summary of Project :


First step involved importing APIs to call weather, wine and soil data. The data was collected from Global Wine Scores, NOAA, and the USGS website. It was then cleaned and finally merged together. Data was split between white wine and red wine before the weather and soil data was merged with it. The Global Wine Scores website has data for wines, the regions that they were grown in, and the scores associated with each wine. These vintages range from 1992 to 2016 and have an average score of approximately 91%. The wine data takes different wines and scores going back to 1992.Some of the challenges for finding the best weather data was to find zip codes that have reliable temperature and precipitation data. Most of the zip codes had data that originated before 1992 but the stations had missig dates for temperature, precipitation, or both of the values. The process for finding optimal stations involved an iterative process of importing different zip codes for temperature data and different zip codes for precipitation data to determine which zip codes have the best coverage of data. Another challenge to merging weather and wine data was that several appellations (regions) within a state straddled two different zip codes. One of the assumptions this study has made was that weather data would be the same for zip codes that were within 50 mile radius of one another. This allowed the group to assign zip codes for certain appellations and allowed the data to be merged together more succinctly. The wine data comes from wine that is concentrated in Washington State, Oregon, Napa Valley California, Sonoma County California, and the Santa Cruz Mountains in California as well. There were some appellations that only have one or two data points that were dropped from the study.

The data was connected through primary keys (unique values in the main table).Once the relationship of the database was created, we use AWS to read and write data from our notebook to and from SQL. In SQL, we join soil table to the red wine table, and soil table to the white table.

Model Choice, Benefits & Limitations:

* Deep Learning Neural Network - The limitation of the model is that it requires a large amount of data and it's not easy to comprehend. The benefits of this model can solve complex problems.

* Random Forest Classifier - The limitation is that features need to have some predictive power to work. The benefit is handling of huge amount of data, No problem of overfitting

* Logistic Regression - The limitation of the model is that it can be easily outperformed by sturdier model like Neural Networks, also its high reliance on a proper presentation of your data. The benefits of this model are that it's easier to implement, very efficient to train and it outputs well-calibrated predicted probabilities.



We chose the Logistic Regression model as the best fit model for this analysis after trying multiple models and considering the structure of our data to help answer our questions.


Flask App/HTML:

https://groupfive-wine.herokuapp.com/


