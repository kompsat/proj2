# Project 2 README
1. Names:
- Wil Hoppin, James Yang

2. UNIs:
- wwh2121, dy2471

3. PostgreSQL account info:
- psql -U dy2471 -h 34.75.94.195 -d proj1part2
- id: dy2471, pw: 9989

4. 

The name and UNI of both teammates. If you changed teammates with respect to Project 1, please indicate whose Project 1 project you have expanded for Project 2 and who the TA mentor for the project was.
The name of the PostgreSQL account where your database is on our server (i.e., specify which teammate's UNI we should use to identify the database for your team). This is the database on which we will base our grading.
A thorough explanation of the three items above with which you expanded your project. Explain carefully your rationale behind your modifications to the schema and how these modifications fit within your overall project.
If you added a trigger, explain carefully what it is meant to achieve and why. Also include in your README file a real example of an "event" (i.e., an insertion, deletion, or update of a relation in your database, as specified in your trigger definition) that causes the trigger to be executed, together with a clear explanation of what the trigger does as a result of the event, including listing clearly any modifications to the database that happen as part of the trigger. Your description should be detailed enough so that we can recreate on your PostgreSQL database the execution of the trigger exactly as you describe it, and part of your grade will be based on the quality and accuracy of this description.
Substantial, meaningful queries involving the new attributes and tables in your schema, with a sentence or two per query explaining what the query is supposed to compute. If one of your three added items is a trigger, then you need to submit two queries (in addition to the trigger information in the previous bullet); otherwise, you need to submit three queries. All your new attributes and tables should appear at least once in one of the queries that you submit. For a text attribute, make sure at least one of your queries uses full-text search, as described here. For an array attribute, make sure at least one of your queries accesses elements in the array. Overall, your queries should work over your PostgreSQL database as submitted. We will run them against your database and part of your grade will be based on them, so please choose your queries carefully. We strongly suggest that you submit well formed queries that run without problems, so please make sure that you have tested your queries by running them on your database exactly as submitted (use copy and paste).