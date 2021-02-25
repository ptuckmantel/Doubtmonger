# Doubtmonger
Project aim: Create an algorithm that flags contrarians of established science for further research of their funding, affiliation and general background.

Status:
Raw datasets have been generated. Filtering needs to be done to weed out "believing" articles from the denying articles dataset and vice versa.


Basic methods:
	1. Scrape the web for news articles on a topic (global warming, vaccines, etc)
	2. NLP classificatier: Identify deniers from non-deniers
	3. Do particular authors of negative news articles appear regularly? Or do some affiliations?
	4. WebScrape WebOfScience: Do authors of negative news publish in scientific journals? Extract a histogram of the published papers broken down by journal to identify (manually) if the authors publish but in predatory journals

Comments:
This works on the assumption that deniers use particular language structures in their articles, which is yet to be verified. However, the classifier does not need to be very accurate as its main goal is to identify spreaders of information and flag the newspapers and authors covering the most negatively. In that sense, the algorithm is there to flag potentially compromised news sources for human investigation, decreasing the total human workload.

