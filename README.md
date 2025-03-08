# DSA210 Term Project - Caffeine Consumption

## Project Overview
 My aim for this project is to explore and investigate the effect of exams and important events on my weekly caffeine consumption throughout my sophomore year. I plan to log down whenever I consume coffee, tea or energy drinks etc. and will then compare my weekly consumption of these drinks with the exam weeks. By the end of this project, I plan to review my consumption of caffeine and to control the consumption to reasonable levels if required.
 
---
## Motivation
 As a person who consumes huge amounts of coffee and tea on a daily basis, caffeine has become a significant thing in my daily life. I have realized that especially during midterms and finals weeks I consume even more caffeine. With the tools of data science, I will process this consumption of mine and hopefully end up with information on how much caffeine I consume regularly and how much effect the exams have on the consumption.
 
---
## Project Plan

 - **Dataset Description**
   - **Caffeine Consumption:** This will be calculated under 2 parts which are logs of coffee consumption pre-project and the logs of coffee/tea/energy drink consumption during the project period. To calculate the weekly intake, the average caffeine content (in milligrams) of every distinct drink will either be calculated using information provided by the providers or will be calculated manually using openly accessible information. The caffeine taken from other drinks from coffee, tea or energy drinks will be collected under another title called "Other".
   - **Exam Dates:** The dates of both the midterm and final exams of the last semester and the current semester will be used. The dates will be used to classify the periods for the consumption of caffeine. These periods are to be:
     - Consumption within 1 week before an exam.
     - Consumption within 3 days before an exam.
     - Consumption within a day before an exam.
     - Consumption on the day of an exam.
- **Collection of Data**
  - The data for the pre-project coffee consumption will be requested from the companies that the coffee was bought from, in case I am unable to get the data directly from them, I will manually log the data into a file by just reading the already accessed purchase history in the apps. For the consumption data that are to be collected during the project period, the consumed product will first be noted down and will then be logged at the end of each day.
  - The data for the previous and current midterm and final exam dates will be taken from my personal Google Calendar, which is updated regularly.
- **Preparation of Data**
  - The data for caffeine consumption is to be calculated carefully as described in the dataset description part above to prevent any inconsistencies.
  - An important thing to track is to eliminate outlier data (which may be caused by non-exam events) to achieve consistency.
---
