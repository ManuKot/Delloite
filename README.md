# Deloitte
Using a data unification algorithm, the tech team at our client, Daikibo, has converted all telemetry data collected from its 4 factories:

Daikibo Factory Meiyo (Tokyo, Japan)
Daikibo Factory Seiko (Osaka, Japan)
Daikibo Berlin (Berlin, Germany)
Daikibo Shenzhen (Shenzhen, China)
Each location has 9 types of machines, sending a message every 10 mins. Daikibo has been collecting this data for one month (May 2021) and they've shared this data in the form of a single JSON file.

The reason the client wanted to collect telemetry was to answer 2 questions:

In which location did machines break the most?
What are the machines that broke most often in that location?


After a worrisome number of internal complaints about gender inequality in terms of salary, Daikibo Industrials wants us to help them investigate.

The Forensic Tech team has built an algorithm to quantify “level of gender pay equality” for most job roles within the company, in all company locations. Our Forensics lead thinks it would be a great idea for you to finish the job.
We have processed all data on employee compensation and generated an Excel file (Equality Table.xlsx, available in the Resources) containing 3 columns:

Task-2
Factory
Job Role
Equality Score (integer; ranging between -100 and +100; 0 is ideal)


Create a 4th column (Equality class), classifying the equality score into 3 types:
Fair (+-10)
Unfair (<-10 AND >10)
Highly Discriminative (<-20 AND >20)
Examples:

6 → Fair
-9 → Unfair
-30 → Highly Discriminative
Please find the Equality Table you need to edit in the resources below. When you are done, upload the edited version of the file.
