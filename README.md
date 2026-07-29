# sql-examples
Reusable SQL queries and examples for cleaning, aggregating, and reporting clinical and behavioral health data from the Credible EHR system. 

File Descriptions:

Urgent Call to Crisis Service Time Analysis --> The output of the SQL is used by our Quality Assurance Team for quarterly efficiency checks.
Client SUD Relapses --> The output is used by the Substance Use Disorder (SUD) program manager for federal grant reporting. Carefully review the 
    date parameters at the beginning because they can be a little difficult to follow. All client, program, and employer information has been changed 
    or removed.
All Client Demographics --> query created for my employer, extracts client demographic data from our EHR system. The CASE expressions help to transform 
    the numeric EHR demographic data into string data in the final table. The table created from this query is then feed into our SSRS and/or Power BI 
    dashboards utilized by our end users. Any employee or client names mentioned in the original code have been redacted.
