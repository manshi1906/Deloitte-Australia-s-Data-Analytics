# Deloitte-Australia-s-Data-Analytics
# TASK1
Daikibo's tech team has converted all telemetry data collected from the 4 factories of the company:

Daikibo Factory Meiyo (Tokyo, Japan)
Daikibo Factory Seiko (Osaka, Japan)
Daikibo Berlin (Berlin, Germany)
Daikibo Shenzhen (Shenzhen, China)
Each location has 9 types of machines, sending a message every 10 min. Daikibo has been collecting this data for 1 month (May 2021) and they've just shared this data in the form of a single JSON file. The reason this client wanted to collect telemetry was to answer 2 questions:

In which location did machines break the most?
What are the machines that broke most often in that location?
By completing this task, I learned how to use the famous Analytics tool Tableau to build an interactive dashboard that helps the Daikibo's tech team to answer their questions.
Your task is to analyse the telemetry data collected by Daikibo in a software called Tableau. Here are the steps that you need to take:

Download the free trial of Tableau (link in the Resources).
Install Tableau on your computer and register an account with the same email you used to download the software.
Download the daikibo-telemetry-data.json.zip file -> unzip -> and import it in Tableau.
Create a calculated measure field called "Unhealthy" with a value of 10 for every unhealthy status (representing 10 mins of potential down time since the previous message).
Create a bar chart called “Down Time per Factory”.
Create a new sheet with a new bar chart called “Down Time per Device Type”.
Create a Dashboard with the 2 previous sheets and set the first chart to be used as a filter (selecting a factory in the first chart shows only the down time of the machines in this factory in the second chart).
Select the factory with the most down time (click on its bar), make a screenshot of the dashboard and upload it as a submission for this task.
Please find a step-by-step Task Guide pdf attached in the resources below to help you out.
# Task 2: Forensic technology
Here is your task
We have processed all data on employee compensation and generated an Excel file (Equality Table.xlsx, available in the Resources) containing 3 columns:

1.Factory
2.Job Role
3. Equality Score (integer; ranging between -100 and +100; 0 is ideal)
Here is your task:

Create a 4th column (Equality class), classifying the equality score into 3 types:
Fair (+-10)
Unfair (<-10 AND >10)
Highly Discriminative (<-20 AND >20)
Examples:

10 → Fair
-9 → Unfair
-30 → Highly Discriminative
Please find the Equality Table you need to edit in the resources below. When you are done, upload the edited version of the file.

 
