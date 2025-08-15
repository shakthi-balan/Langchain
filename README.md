# Langchain
## Linkedin Search Agent

### **** Important Links ****
##### ReAct : Reasoning & Acting Research Paper
https://arxiv.org/pdf/2210.03629

##### Prompt Template
https://smith.langchain.com/hub/hwchase17/react

##### APIs used
Scrapin.io - Linkedin Data \n

Tavily     - Web Search API



### Methodology Used

##### Lookup Agent :
AI Agent Looks for the top linkedin Urls by using available tools - Web Search( Tavily ) and returns a url.

##### Scrape_url : 
Gets all the linkedin account information using Scrapin.io API

##### LLM : 
Summarizes the retrieved data.
