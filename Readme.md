# CentralQ.ai
"AI search, fueled by the collective knowledge of Business Central community."

**CentralQ.ai** is an AI-powered search engine that utilizes the collective knowledge of the Business Central community to provide accurate and relevant answers to your queries.


## Stack

CentralQ.ai makes use of the following APIs:

- **Knowledgeable** - Content from Microsoft Learn and blogs, used for semantic search.
- **Qdrant** - A semantic search vector database provided by Qdrant (https://qdrant.tech/).
- **OpenAI** - An answer generation API provided by OpenAI (https://openai.com/).
- **Upstash** - A Redis-based caching service provided by Upstash (https://upstash.com/) for rate limiting.
- **Azure Tables** - A NoSQL database service provided by Microsoft Azure (https://portal.azure.com/) used to store search logs.
- **Google Analytics** - A web analytics service provided by Google (https://analytics.google.com/).
- **Python anywhere** - A hosting service provided by Python Anywhere (https://www.pythonanywhere.com).

## Rate Limits

CentralQ.ai enforces the following rate limits to prevent abuse:

- 3 requests per minute per user.
- 60 requests per day per user.

## Usage

To use **CentralQ.ai**, simply visit the website (https://www.centralq.ai) and enter your query in the search bar. **CentralQ** will utilize the APIs mentioned above to provide you with a relevant and accurate answer.

## Support

- You can make contributions to the knowledgebase csv files, to add more valuable blogs.
- When using **CentralQ**, feel free to provide a feedback, by clicking on thumb up/down and a feedback text. This could be a better answer or description of what's wrong or, I hope,  your awesome feedback :) **CentralQ** will use this info to provide better answers next time. 

If you encounter any issues while using CentralQ.ai or have any feedback, please contact us at dmitry@katson.com.
