---
layout:     post
title:      Defining "data science"
subtitle:   Will this be a lasting name or fade like "big data"?
date:       2016-02-29 02:00:00
author:     "Dimitri Semenovich"
header-img: "img/post-bg-01.jpg"
---

{%newthought 'Increasing number of industries'%} is being affected by “digital transformation – new business models facilitated by the ubiquitous availability of computing and telecommunication technologies. This “digital transformation” is to a large degree carried out by engineering / software centric “web” companies following technology practices that have little overlap with traditional enterprise IT.


“Data science” then roughly amounts to “analytics at web companies”. The particular setting of course has an impact on how the “analytics” are produced and consumed (primarily manifesting as greater degree of automation due to volumes of data and timescales to generate results ), yet due to the wide front of “digital transformation”, only some high level patterns can be discerned.

Specifically, “analytics” is the process where some manner of systematic measurements and observations are used as a presumably objective basis for making decisions, delivering process improvements or optimising (more or less abstract) performance metrics. The same theme is repeated with variations across a wide gamut of loosely associated disciplines. Exact definitions have proven notoriously elusive, with few convincing distinctions from the classical notions of rational or scientific inquiry other than through the domain of application.

Below is a very imperfect attempt at grouping together various academic sub-disciplines and professions (omitting actuaries) that could be broadly said to be involved in analytics. The association is through a subjective assessment of closeness of intellectual tradition.

 **Online advertising and website optimisation** – online advertising has grown into a massive ecosystem over the last two decades providing revenue for the majority of online services. The nature of the medium is eminently accommodating of tracking and analytics, resulting in one of the more dramatic applications of “data science”. Most sophisticated solutions (e.g. Adwords) are deployed by  inventory providers and aggregators, such as Google and Facebook. Live A/B testing is also prevalent among online businesses – something which is still a rarity in traditional enterprise. This is at present the biggest area of employment for “data scientists”.

**Manufacturing quality control**, statistical process control, lean manufacturing, six sigma – this is an area of analytics activity supporting manufacturing activities and has been progressively developed since at least 1930’s. Among the main objectives is monitoring and elimination of variability in manufacturing processes (e.g. part dimensions), ensuring that defect rates are thereby controlled.

**Scientific management**, management consulting, management accounting – the broad idea of application of “scientific” principles to industrial management is well over 100 years old – ubiquitous proliferation of plans, budgets, KPIs and management reports is part of this tradition. Very little attention is usually paid to natural statistical variation in many metrics. Also while many controlled experimental studies have been documented in this setting they have never become a part of the standard methodology.

**Operations research**, industrial engineering, revenue management, mathematical optimisation, management science. Operations research began as scientific study of military operations (e.g. convoy composition, bomber interception protocols, logistics) during the second world war and the principles have been exported to many other industries in the following years. Main tools include mathematical optimisation, stochastic processes. Mathematical optimisation is a somewhat standalone area of research with many close connections to both computer science and statistics.

**Statistics**, - really requires no introduction, perhaps the main focus of interest in applications has been analysis of government data, polls and surveys and support for evaluation of experimental results in life sciences and medicine.

**Applied finance**, financial engineering, algorithmic trading, HFT, risk management. There are close parallels between data science and quantitative finance in the 1980s and 1990s. This is not surprising, because in market execution is a key part of any model driven trading strategy, placing a premium on  “hacking skills”.  At present it is perhaps reasonable to view majority of  “data scientists” as “quants” of digital advertising.

**Engineering control**, control theory, signal processing From fly-by-wire systems to cellular networks and  synthetic aperture radar. Much less ambitious in scope than AI, but this systems work reliably and are by now absolutely ubiquitous.

**Econometrics**, mechanism design, causal inference (from observational data) – due to the difficulty and costs of real world experiments in economics, econometricians have developed tools and conceptual frameworks for causal inference with observational data. Furthermore mechanism design and the study of auctions have had significant impact on the design of online marketplaces.

**Business intelligence**, database / warehouse design, dashboards –business intelligence is primarily IT vendor driven activity to support management reporting in traditional enterprise with perhaps strongest intellectual links to the academic databases research community. Traditionally little attention has been paid to statistical aspects of “business intelligence” or how it is to be actioned.
 
**Machine learning**, natural language processing, computer vision, data mining – machine learning is a branch of computer science that initially focused on more tractable aspects of artificial intelligence, primarily by constructing models from example data using statistical methods rather than designing them by hand from general principles. Two large application areas are computer vision and natural language processing, including machine translation. By now the differences between theoretical machine learning and statistics communities is largely superficial, amounting to little more than preferences for different styles of analysis of statistical procedures. Machine learning research has also provided many  of the tools used in analytics for online advertising and algorithmic trading. Data mining has originated from the databases research community and by now has mostly converged with machine learning in terms of both objectives and methodologies.

Analytics landscape is difficult to survey for no other reason that many movements have overlapped in time and areas of practice, resulting in a layering of ideologies and ideas perhaps impossible to decisively disentangle. It is, however, fair to say that the mixtures of ideas are not the same between economic sectors, allowing for an analysis or classification from this point of view.

While most “analytics” traditions claim to use “data” to produce good (or at least informed) decisions, the level at which they operate can vary enormously. At the lowest level, some processes are completely automated (e.g. many applications of engineering control, such as fly-by-wire systems). Other traditions best apply to low level manufacturing processes (SPC). On the other end, econometrics is often used to evaluate high level government policies and management consultants provide decision support at the board and executive level.

One should be wary of attempts to create an appearance of history for the term “data science” (as, e.g. in the Wikipedia article as of fall 2015). As with any two common words it is perhaps inevitable that they have been used together at some point in the past, but the uses going beyond 2008 - 2010 are of unclear relevance. A more compelling account of the history of data science was recently given by David Donoho{%sidenote 'One' 'Donoho, D. (2015). [50 Years of Data Science](http://courses.csail.mit.edu/18.337/2015/docs/50YearsDataScience.pdf). Tukey Centennial Workshop, Princeton'%}, considering it in the context of the broader evolution of the practice of data analysis.

While there is a good chance that "data science" will become an umbrella term for a partial rejoining of the many streams of analytics, separated in some cases by nearly a century, it is at present lacking a strong intellectual undercurrent. Indeed, quoting Gian-Carlo Rota:

>"When pygmies cast such long shadows, it must be very late in the day."

