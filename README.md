# NASA Apache Log Analysis using Pyspark

## Project overview
This project analyses NASA web server logs using PYSPARK
The goal is to convert raw log entries in to structured data and perform the analysis to understand website traffic pattern.
## Team members
- Data preprocessing(Pyspark)
- Data Analysis
- Visualizations & report

## Dataset
Dataset used-NASA wen server Logs(August 1995)

Raw log contains entries like: 
piweba4y.prodigy.com - - [01/Aug/1995:00:00:10 -0400] "GET /images/launchmedium.gif HTTP/1.0" 200 11853

Fields extracted:
- host
- timestamp
- method
- url
- status
- size

## Technologgies used
- Python
- Pyspark
- Jupyter notebook
- Github

## Projecct WorkFlow
Raw NASA log files --> Data preprocessing --> Structured Dataset --> Data Analysis --> visualizations.

## Analysis performed
- Peak Traffic Hours
- Most Frequently Accessed URLS
- Distribution of HTTP status code
- Average response size

## Future scope
Future improvements include implementing real time log monitoring and anomaly detection using Streaming frameworks such as Apache Kafka and saprk streaming.

## Conclusion
This project demonstrates how large web server logs can be processed using Pyspark to extract insights about website traffic and system behaviour.
