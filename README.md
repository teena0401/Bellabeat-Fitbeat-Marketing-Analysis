# Bellabeat

###Introduction 
This case study is the final project in the Google Data Analytics Professional Certificate course. In the case study, I’ll be analyzing a public dataset provided by the course as if I were working with the Marketing and Product departments as a data analyst at the health and wellness company Bellabeat.

####About Bellabeat 
Bellabeat is a wellness company based in San Francisco, California that develops smart technology for women. Their mission is to empower women by providing them with the data to discover themselves.

Bellabeat products are available through a growing number of online retailers in addition to their own e-commerce channel on their website.

##### Scenario 
Bellabeat is a successful small company with the potential to become a larger player in the global smart device market. Urška Sršen, cofounder and Chief Creative Officer of Bellabeat, believes that analyzing smart device fitness data could help unlock new growth opportunities for the company. I’ve been asked to focus on one of Bellabeat’s products and analyze smart device data to gain insight into how consumers are using their smart devices, which will then be used to guide marketing strategy for the company.

#### Business Task 
Analyze smart device user data to gain insight into how consumers are using their non-Bellabeat smart devices (in this case, FitBit), and apply these insights to comparable Bellabeat products such as the Bellabeat Leaf.

### About the Data 

The dataset for this case study, FitBit Fitness Tracker Data, was provided by Google through the data science website Kaggle. The dataset was originally generated by respondents to a distributed survey via Amazon Mechanical Turk. The survey spanned a 30-day period starting April 12th, 2016 to May 12th, 2016.

The three tables I analyzed from this dataset are dailyActivity_merged, sleepDay_merged, and weightLogInfo_merged, renamed DailyActivity, SleepLog, and WeightLog, respectively.

####Limitations

Most likely, the data isn’t representative of all FitBit users. Only 33 people took part in the survey. The largest table in the dataset, ‘dailyActivity_merged’, for example, contains 15 columns—almost half as many attributes as participants.
Roughly a quarter of the participants didn’t record any sleep data. Three quarters of participants didn’t record weight data.
The data is old. Both FitBit and Bellabeat have come out with new products and features since 2016. Smart device usage, like the devices themselves, has likely changed since then.
The data comes from a third-party source with no way to examine credibility or potential biases.
Participants weren’t asked to wear/use their FitBits for the entirety of the 30-day period, so some records are missing.

### Preparing Data for analysis 

### Processing and Analysis of Data 

### Data Visualization 

Sleep [ Average Hours of Sleep per day of week ] 
2. Total Minutes of Sleep Vs Sendentary Minutes x4 
3. Total Minutes of Sleep vc Total Sleep 
4. How many minutes on average it takes to fall asleep by day of week 
5. How many minutes to fall asleep 

Calories 
1. average calories burned per day of the week 
2. Calories burned vs Sedentary Minutes (x4) 
3. Calories Burned vs Step taken 
4. calories burned vs total distance (x4) 

Activity 
1. Average Steps taken per day of the week 
2. Average Distance(in Kilometer) per day of the week 
3. Percentage of Time Spent in different levels of activity across entire study 



### Conclusion 
- Sedentary make up a significant portion, 81% of users daily active minutes. Users spend on avg 12 hours a day in sedentary minutes, 4 hours lightly active, and only half-hour in fairly+very active!
- We see the most change on Saturday: users take more steps, burn more calories, and spend less time sedentary. Sunday is the most "lazy" day for users.
54% of the users who recorded their sleep data spent 55 minutes awake in bed before falling asleep.
- Users takes the most steps from 5 PM to 7 PM Users who are sedentary take minimal steps and burn 1500 to 2500 calories compared to users who are more active, take more steps, but still burn similar calories.

- In a period of a month (April to May 2016), there were 83% of users in Vigorous category when it came to how frequently they wore their tracker.
Most of the users were not active, as sedentary minutes show the highest value.
73,5% users were not reaching 10.000 steps a day.
Wednesday and Sunday made up to the most active day.
- Higher steps spent means that higher calories was burnt.
The highest average time in bed within a week falls on Tuesday.

There is no significant correlation between steps, calories, and total minutes asleep.
The more intense users worked out, the better for them to reach their weight goal.

#### Findings

-	User experience of bellabeat product is positive as 90% of existing users wear for more than 21 days in a month. 
-	On average, each user spends half their day on sedentary activities and less than 2 hours altogether on very active and fairly active activities (1 hour 12 mins).
-	Evening period, 5pm to 7pm, has the highest average steps count throughout a day followed by afternoon to noon period, 12pm to 2pm, which has the second highest count. 
-	Users are less likely to wear during sleep, where only 10 users, out of 24 users, have worn more than 15 nights. 
-	There is a positive correlation between activity level and calories burned. The more activity you are, the more calories you burn   

#### Recommendations 
- Obtain more data for an accurate analysis, encouraging users to use a wifi-connected scale instead of manual weight entries.
🚲 Educational healthy style campaign encourages users to have short active exercises during the week, longer during the weekends, especially on Sunday where we see the lowest steps and most sedentary minutes.
🎁 Educational healthy style campaign can pair with a point-award incentive system. Users completing the whole week's exercise will receive Bellabeat points on products/memberships.
🏃‍♂️ The product, such as Leaf wellness tracker, can beat or vibrate after a prolonged period of sedentary minutes, signaling the user it's time to get active! Similarly, it can also remind the user it's time to sleep after sensing a prolonged awake time in bed.
