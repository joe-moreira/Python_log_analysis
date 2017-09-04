# Python_log_analysis
Python script which analyzes logs for key-words and in case of found them, collects more information and stores the info in a SQLite3 DB.

My company is selling a product which is permanently generating logs tracking its activity. When a customer experiences a failure, the logs have to be checked and fully analyzed. The following program was created to be executed after customer communicates the issue and its main goal is to accelerating a troubleshooting process and speeding up a customer’s solution response.
The code is executed on customer premises and provides a first log’s check output and some primary conclusions which can be useful for latter and quicker decisions taken.

