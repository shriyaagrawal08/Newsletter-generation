# Implemented


1- added user_topic -> llm -> output
2- added streaming in output result ( so that result should come word by word)
3- also added time limit like 50 milliseconds to generate each word by word, its more user engaging this way.
4- added temp=0.2 to model
5- Integrated MCP tools with LLM 

MCP Tools include ->

a) Tavily MCP - Web search and extraction
b) RSS ingestion - TOI, Hindu, ET, etc.
c) GitHub MCP - trending repositories
d) arXiv API - Research papers

6- Prompt Engineering is used in "prompt" in newsletter_flow method.
7-
8-
9-
10-



# can implement it later 

1- langsmith --> not getting added, will implement it later
2-
3-
4-



# Oppositions ( for FDE role )

1- Memory (long term only for our usecase) -> like when user login -> it remember its old unique id + its old preference -> generate newsletter accordinlgy

if user signup for first time -> remember its choice and generate newsletter accordinlgy for current time and later use when it login

Opposition --> but user will generate topic acc to his choice everytime...so whats the use of remembering his preference...see the newsletter will be generated based on a certain topic...not "genrate me a newsletter" thats is... in this case it should remeber choice...when its generating based on topic...it should not need memory

SO WE WONT BE REQUIRING MEMORY


2- 