---
layout: project
color: "#0088BD"
logo: General Prefetch Framework
---

<div class="callout">
</div>


Interactivity is a core requirement for a wide range of user-facing applications, including data visualizations, web search and games. These user-facing, interactive apps must achieve low latency responses in order to satisfy users, which cannot always be met by waiting for a user's decision before reacting. An alternative is to pre-fetch data in anticipation of users' choices. There are several limitations to existing uses of prefetching: (1) it is often developed in an adhoc way for each application, and does not consider all optimization aspects, and (2) they do not explicitly take advantage of the approximation tolerant nature of many interactive applications. Approximation tolerance means that users prefer fast but approximated, over fully correct but slow, results.

This project designs a General Prefetching Framework called GPF that explicitly decouples prediction and scheduling from the client application. A configurable prediction model estimates the likelihood of requests at different future time intervals, and a general scheduler uses these predictions to decide which requests to send to the client. This framework is novel in several ways: (1) rather than explicit requests, the client occasionally offers predictions to the scheduler, which considers network and resource conditions when pushing results to the client, (2) GPF exploits application tolerance to send partial results for a massive number of candidate requests, rather than full results for a few requests, and (3) GPF dynamically shifts placement of the predictor and scheduler computation on the client or server based on latency, network, and resource conditions.

The supporting research brings together performance and scheduling ideas from the networking community with optimization, storage, and interaction ideas from the database and visualization communities. GPF will integrate and eliminate user-perceived application latency in applications across multiple domains, including data visualization, media players, webpage navigation, vehicular control, and games. The multidisciplinary research (networking, information visualization, and database systems) will be integrated into courses on data science, databases, networking, and visualization. Software will be open sourced, and will have significant, long-term impact on the way interactive applications are developed. The outcomes of the research and education material will be disseminated via workshops, publications, and open-source repositories. These education and outreach plans will further increase participation in this multidisciplinary topic that will lead to the continuing advancement of big data visualization techniques, network scheduling and prioritization designs, and ultimately benefit the increasing number of domains that rely on, or demand, interactive applications to make time critical decisions and discoveries.


## Principal Investigators

* Eugene Wu, Columbia University [NSF 1564049](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1564049&HistoricalAwards=false)
* Daniel Rubenstein, Columbia University 
* Ravi Netravali, Princeton University

<!--## Open Source Software-->

