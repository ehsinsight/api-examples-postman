# Summary
This Postman Collection demonstrates the following API actions:
* Entity Definition List
* Entity Record List
* Entity Fetch
* Entity Fetch
* Entity Create
* Entity Update
* Entity Delete
* Folder List
* Folder Create
* Folder Delete
* BusinessHierarchy List
* BusinessHierarchy Fetch
* BusinessHierarchy Create
* BusinessHierarchy Update
* BusinessHierarchy Delete
* Role List
* Discussion List Form Discussion Comments
* Discussion Add Form Discussion Comments
* Discussion Redact Form Discussion Comments
* Discussion Vote Form Discussion Comments
* Report List
* Report Schema Fetch
* Report Execute
* Report Execute with Named Query
* Attachment Create
* Attachment Fetch

Full API Documentation is located at **Help / API Documentation**.

The examples can be adapted to cover additional entity types by referencing **Help / Schema Explorer** to discover additional entity names and property types.


# Caution
DO NOT RUN API EXAMPLES AGAINST A PRODUCTION SITE.

Please request a **SANDBOX** site for API experimentation and development.

# Instructions

1. In Postman navigate to the `Collections` tab and click Import.
1. Select the `.\Collections\EHS Insight API.postman_collection.json` file.
1. Edit the Postman Collection variables and set the current value of the `siteApiKey` variable with your API key found in EHS Insight under **Administration / API Settings**.
1. Edit the Postman Collection variables and set the current value of the `siteUrl` variable with your EHS Insight base URL.
    * ex https://test.ehsinsight.com
1. Set route variables to target the action that you are intending to accomplish.
1. Query parameters are optional but can be set to narrow down a dataset.
1. Request bodies are present as examples but they may not work due to Guids being available/unavailable in your environment. Be sure to edit these.

# License
This repository contains programming examples.

EHS Insight grants you a nonexclusive copyright license to use all programming code examples from which you can generate similar function tailored to your own specific needs.

All sample code is provided by EHS Insight for illustrative purposes only. These examples have not been thoroughly tested under all conditions. 

EHS Insight, therefore, cannot guarantee or imply reliability, serviceability, or function of these programs.

All programs contained herein are provided to you "AS IS" without any warranties of any kind. 

The implied warranties of non-infringement, merchantability and fitness for a particular purpose are expressly disclaimed.
