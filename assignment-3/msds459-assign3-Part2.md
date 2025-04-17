# Part 2

## Summary of Chapters 3 and 5:

### Chapter 3: Domain Discovery (Pages 53–76)

Various issues with crawling include 

Crawler evalutation using 'ground-truth' technique.

This chapter focuses on the process of domain discovery within the context of knowledge graph construction. Domain discovery involves identifying and extracting knowledge relevant to a specific subject area from various sources. The authors describe several methodologies and techniques for performing domain discovery effectively.

Focused crawling is the primary focus and is related to the retrieval and organization of information from the web. Focused crawling is a web crawling technique that aims to gather content from the internet specifically related to a particular topic or domain. It uses algorithms that prioritize the retrieval of pages based on their relevance to a predefined topic, utilizing link analysis and content analysis to guide the crawling process. A **Seed-based** approach is used where a small set of known entities or examples are used to discover related concepts and instances. This 'seeding' is a type of input mechanism. Three type of Focused crawlers are described in detail.

**Best-First cralwers** are discussed which are described as a type of web crawler that prioritize the retrieval of web pages based on their estimated relevance to a specified topic or query. These crawlers utilize heuristics, such as keyword matching, link analysis, and content analysis, to evaluate which pages are likely to yield the most pertinent information, thus optimizing the crawling process by focusing on the most promising sources first. Another type crawler disscussed is the **semantic crawler** which is a web crawler designed to analyze and extract structured data from web pages using semantic technologies, such as ontologies and metadata, to understand the meaning of the content and facilitate more meaningful search and retrieval of information. The third crawler, **Learning crawlers**, are advanced web crawlers that utilize machine learning algorithms to improve their crawling strategies over time by learning from previously crawled data, enabling them to adaptively prioritize and retrieve the most relevant and useful information based on user interactions and content features.

The evaluation of focused crawling involves assessing the effectiveness and efficiency of the crawling process in retrieving relevant content for a specific topic while minimizing the acquisition of irrelevant or low-quality pages. Key metrics used in this evaluation include precision (the proportion of relevant pages among the retrieved pages), recall (the proportion of relevant pages that were successfully retrieved), and overall coverage of the targeted domain, which together help determine the crawler's performance and effectiveness in meeting its objectives.

### Chapter 5: Web Information Extraction (Pages 97–124)
