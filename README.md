Setup:
spin up the docker compose: This runs the master and the 4 worker node [command: docker-compose up -d]
submit the visual.py file which is our job file  to the master[command:docker exec -it "master node id" spark-submit --master spar://172.18.0.2:7077 jobs/visual.py]

Data Input:
Place the CSV file named "visa_number_in_japan.csv" in the "input" directory of your project.

Run the Script:
Execute the provided Python script by submitting this to the spark master . This script likely performs data processing tasks such as cleaning, analyzing, or visualizing the data.

Visualizations:
After executing the script, you'll find the visualizations saved as HTML files in the "output" directory. These visualizations are likely generated from the processed data to provide insights or summaries.

Cleaned Data:
The cleaned data will also be saved as a CSV file in the "output" directory. This CSV file contains the processed and cleaned data ready for further analysis or use.

Output
![Alt Text](https://github.com/pandey0/spark_visaData/blob/master/Screenshot%20from%202024-02-20%2000-56-39.png)

![Alt Text](https://github.com/pandey0/spark_visaData/blob/master/Screenshot%20from%202024-02-20%2000-57-10.png)

![ALT TEXT](https://github.com/pandey0/spark_visaData/blob/master/Screenshot%20from%202024-02-20%2000-57-32.png)
