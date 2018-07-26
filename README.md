# qtm4j-postman-collection

Postman Collection contains HTTP requests for uploading test result file on JIRA instance using [QMetry for JIRA - Test Management](https://marketplace.atlassian.com/plugins/com.infostretch.QmetryTestManager/cloud/overview).

### Steps to follow

1. [Download](https://www.getpostman.com/) Postman app if you don't have. 
2. [Import](https://www.getpostman.com/docs/postman/collections/data_formats) Cloud or Server collection in your Postman App. 
3. Provide necessary request params. 
  ##### JIRA Cloud
  1. In first HTTP request provide your details. For more info about request params refer [QMetry docs] (https://qmetrytestdocs.atlassian.net/wiki/).
  2. In second request, select your test result file. 
  ##### JIRA Server
  1. In HTTP request provide your details. For more info about request params refer [QMetry docs] (https://qmetrytestdocs.atlassian.net/wiki/).

### Run Collection

Once you fill request params and upload file, its time to run this collection. 

You have 2 options. 

1. You can run POSTMAN collection directly. [Like this](https://www.getpostman.com/docs/postman/collection_runs/starting_a_collection_run)
2. Or you can run each request seperately. After 1st request is completed, copy URL from response and put as request URL in 2nd request. 
