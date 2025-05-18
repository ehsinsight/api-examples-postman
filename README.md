# Summary
This Postman Collection demonstrates the following API actions:
* Entity Definition List
* Entity Record List
* Entity Record Fetch
* Entity Record Create
* Entity Record Update
* Entity Record Delete
* Folder List
* Folder Create
* Folder Delete
* Business Hierarchy List
* Business Hierarchy Fetch
* Business Hierarchy Create
* Business Hierarchy Update
* Business Hierarchy Delete
* Role List
* Discussion List Comments
* Discussion Add Comment
* Discussion Redact Comment
* Discussion Vote
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

#### Setup

1. In Postman, navigate to the `Collections` tab and click Import
1. Select the `.\Collections\EHS Insight API.postman_collection.json` file
1. Edit the Postman Collection variables
    * Set the `siteApiKey` variable with an API key generated in EHS Insight under **Administration / API Settings**
    * Set the `siteUrl` variable with your EHS Insight base URL (ex. `https://yoursite.ehsinsight.com`)

#### Notes
1. Set route variables to target the action that you are intending to accomplish
1. Example request bodies are included but they may require adjustment due to specific RowUIDs matching your environment

# License
This repository contains programming examples.

EHS Insight grants you a nonexclusive copyright license to use all programming code examples from which you can generate similar function tailored to your own specific needs.

All sample code is provided by EHS Insight for illustrative purposes only. These examples have not been thoroughly tested under all conditions. 

EHS Insight, therefore, cannot guarantee or imply reliability, serviceability, or function of these programs.

All programs contained herein are provided to you "AS IS" without any warranties of any kind. 

The implied warranties of non-infringement, merchantability and fitness for a particular purpose are expressly disclaimed.
