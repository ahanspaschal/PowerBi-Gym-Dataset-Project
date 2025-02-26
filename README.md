# PowerBi-Gym-Dataset-Project
![gym pix](https://github.com/user-attachments/assets/596306b1-a48b-402b-a08a-c7282dffdb25)

## Project Objective:

This project is aimed at generating insights on gym members' workout habits and performance metrics, with the goal of
creating actionable recommendations for improving fitness, health, and workout performance, which was visualized in the first page. And also to help gym managers understand the behavioral pattern and trends of their gym members for improved customer satisfaction. The later was visualized in the second page canvas.
## Dataset Used

- <a href="https://github.com/ahanspaschal/PowerBi-Gym-Dataset-Project/blob/main/gym_members_exercise_tracking_synthetic_data.csv">Link To Dataset</a>
## Questions(KPIs)

## First Page(Facility users Dashboard)
- What is the most effective workout type in terms of calorie burnt?
- Relationship between volume of water intake and calories burnt
- Which is the most frequent work out type?
- How long is spent in a workout session on average? 
- Relationship between frequency of workout and average body fat percentage.
- Workout type preference by gender and BMI group.

## Second Page(Managers Dashboard)
- Distribution of members age group
- Gender distribution of gym members
- Members distribution based on their experience level
- Work out type preference by age group
- Total frequency of each workout type for the given period of time

- Dashoard Interaction <a href="https://1drv.ms/u/c/2ffbe0b0e58b637b/Ecf-vH81wdVEif4GWzq8J-IBHIq4tSYVN5ddqvOsw3lqiQ?e=BgPkOR">View Dasboard</a>

## Steps Taken
- Performed extraction, loading and transforming(ETL) process of the dataset.
- On transforming with Powerbi query, I corrected some inconsistencies and errors in the dataset which can affect my visualization. I removed some empty columns. Some numerical column appeared as text column, I changed 
  the data type to numerical. 
- Still on transformation, I utilized the powerbi DAX to create extra columns from existing column. For instance, Age_group column was created from age column, experience_class column was created from experience_level 
  column etc.
- After transformation, the data was loaded into powerbi for and was used to create an interactive and insightful dashboard 
