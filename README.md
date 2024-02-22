# FlightDataSync-Real-Time-Aviation-Data-to-AWS-S3
Flight Data Sync is a Python project designed to retrieve real-time flight data from the AviationStack API and upload it to Amazon S3. The project aims to provide a seamless solution for accessing and storing flight information in a centralized cloud storage system.

**Features**
Real-Time Data Retrieval: Utilizes the AviationStack API to fetch up-to-date flight details including departure, arrival, and airline information.
CSV File Creation: Organizes the retrieved flight data into separate CSV files for departure, arrival, and airline details.
Amazon S3 Integration: Uploads the generated CSV files to Amazon S3 for secure and scalable storage.
Automated Data Sync: Enables scheduled execution for periodic data synchronization, ensuring the latest flight information is always available. **COMING SOON IF COMMENTS**

**Usage**
API Access Key: Obtain an access key from AviationStack to authenticate API requests.
Configuration: Update the AWS credentials and bucket name in the script to enable S3 integration.
Execution: Run the Python script to fetch flight data, create CSV files, and upload them to S3.

**Requirements**
_Jupyter Notebook_: While any Python IDE can be used, Jupyter Notebook is preferred for its cell-wise execution capability, allowing you to run code blocks individually and inspect outputs.
_Python 3.x_
_Requests library_ (pip install requests): Used to send HTTP requests and handle API responses. It is essential for fetching data from the AviationStack API.
_Boto3 library_ (pip install boto3): The boto3 library is the official AWS SDK for Python. It provides an easy-to-use interface for interacting with AWS services, such as Amazon S3. Boto3 is required for uploading the generated CSV files to Amazon S3.

Go to the AviationStack website https://aviationstack.com/ and sign up for an account if you haven't already.
Once logged in, navigate to your account settings or API dashboard.
Look for an option to generate an API access key or token. This key will be used to authenticate your requests to the AviationStack API.

**Challenges**
Challenges may arise during the data retrieval process, such as verifying the API link's correctness and removing any extraneous spaces. 
Similarly, issues might occur while creating CSV files, warranting careful verification of file paths. 
Additionally, challenges may arise during the upload to S3, necessitating the granting of necessary permissions to both the user and the S3 bucket.

**DISCLAIMER**: I have removed all my credentials, so you will need to generate new credentials for accessing the AviationStack API and obtain AWS access keys by creating a role.


IF IT'S HELPFUL LIKE IT THEN START IT.
