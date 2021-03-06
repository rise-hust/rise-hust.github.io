---
title: "SOAR - Research"
layout: textlay
excerpt: "SOftware Analytics Research Group -- Research"
sitemap: false
permalink: /research/
---

<h1 style="font-family: 'Roboto', sans-serif; font-weight: 500; font-size: 32px;">Research</h1>

We work on **the advancement of software analytics**, which is the integration of code and data analysis techniques to reduce software cost and improve software reliability and security. In general, we are interested on how software can be better developed, better maintained, better tested and better debugged through an analysis of the wealth of software data currently available. We are also interested to perform **empirical studies** to understand the pain point of developers, characterize developer current practices and their limitations, and bridge the gap between academics and practitioners.

We are excited to work on software analytics, which is a growing field bolstered with the surge in the amount of software engineering data on the internet and fueled with the need to deal with the complexity of secure and high-quality software development and maintenance.

Our work has been published in **top/major conferences and journals** in the areas of software engineering (ICSE, FSE, ASE, ISSTA, ICSME, PLDI, TSE, TOSEM), artificial intelligence and data science (IJCAI, AAAI, KDD, VLDB, ICDE, ACL), and cybersecurity (ESORICS, TIFS).

Please feel free to browse some of our work below.

###  Bug and Vulnerability Management

We are intrigued to examine the entire process of **how developers manage bugs and vulnerabilities**, and **how a data-driven approach can help**. Our work in this area include:
+ We have designed a comprehensive array of solutions that can identify vulnerabilities and repair them. They include solutions that can identify vulnerable third party libraries by analyzing National Vulnerability Database entries and commit logs, and solutions that can learn from version history to automatically patch vulnerabilities. Examples of these studies include: <a href="/papers/research/Chen2020MLApproachForVulnerabilityCuration.pdf" target="_blank">(Chen et al. 2020a)</a>, <a href="/papers/research/Chen2020AutomatedIdentificationofLibrariesfromVulnerabilityData.pdf" target="_blank">(Chen et al. 2020b)</a>, <a href="/papers/research/Ma2017VuRLE.pdf" target="_blank">(Ma et al. 2017)</a>, <a href="/papers/research/Ma2016CDRep.pdf" target="_blank">(Ma et al. 2016)</a>.

+ We have designed a comprehensive array of novel automated solutions to help developers manage large numbers of bug reports. The solutions include techniques to: identify duplicate bug reports, prioritize bug reports, assign bug reports to developers, locate buggy files given a bug report, and many more. Examples of these studies include: <a href="/papers/research/Sun2010DuplicateBugReportRetrieval.pdf" target="_blank">(Sun et al. 2010)</a>, <a href="/papers/research/Zhou2012WhereShouldTheBugsBeFixed.pdf" target="_blank">(Zhou et al. 2012)</a>, <a href="/papers/research/Hoang2019BugLocalization.pdf" target="_blank">(Hoang et al. 2019)</a>.

+ We have proposed a set of automated debugging solutions that consider on various settings. These include solutions that: identify likely defective files/commits based on version history data (aka. defect prediction), identify likely buggy program elements given test case failures (aka. spectrum based fault localization), construct likely fixes given test case failures (aka. automatic program repair), and many more. Examples of these studies include: <a href="/papers/research/Lo2009FailuerDetection.pdf" target="_blank">(Lo et al. 2009)</a>, <a href="/papers/research/XBD2016ProgramRepair.pdf" target="_blank">(Le et al. 2016)</a>, <a href="/papers/research/Xia2016Hydra.pdf" target="_blank">(Xia et al. 2016)</a>.

###  Code and Documentation Management
Given a large code base, a large set of code repositories, or a large set of libraries, it is often hard to find code snippets, methods or libraries of interest, given a particular need. Additionally, due to the fast pace of software development, documentation is often unavailable or outdated. Our work has addressed these pain points in the following ways:

+ We have designed a number of **code search and recommendation engines** <br> These include solutions that: identify code snippets that match certain structural constraints (aka. structured code search), identify code snippets that match a natural language query (aka. text-based code search), identify APIs that should be used given a particular need expressed in natural language (aka. API recommendation), and many more. Examples of our prior studies include: <a href="/papers/research/Sirres2018AugmentingUserQueries.pdf" target="_blank">(Sirres et al. 2018)</a>, <a href="/papers/research/Huang2018APIRecommendation.pdf" target="_blank">(Huang et al. 2018)</a>, <a href="/papers/research/Rahman2019QueryReformulation.pdf" target="_blank">(Rahman et al. 2019)</a>.

+ We have designed a number of **specification mining engines** <br>
Our specification mining engines infer specifications of how a piece of code or library works by analysing execution traces of its clients. These include solutions that infer specifications in the form of: finite state models, temporal logic constraints, modal sequence diagrams, and many more. The specifications have been used to for various purposes ranging from program comprehension to construction of fine-grained Android sandboxes to prevent malicious behaviours. Examples of our prior studies include: <a href="/papers/research/Lo2006SMArTIC.pdf" target="_blank">(Lo and Khoo 2006)</a>, <a href="/papers/research/Lo2007SoftwareSpecificationDiscovery.pdf" target="_blank">(Lo et al. 2007)</a>, <a href="/papers/research/Le2018DeepSpecificationMining.pdf" target="_blank">(Le and Lo 2018)</a>.

+ We have designed a number of **documentation search and generation engines** <br>
These documentations include textual documents and rich media that can help developers in their tasks. Our prior work has produced solutions that: answer natural language queries from software documentations (aka. question and answer bots), output tags for software question and answer posts (aka. tag recommendation), produce natural language comments for code artefacts (aka. comment generation), supporting serendipitous information discovery on Twitter (aka. software tweet analytics), generate workflows for programming videos (aka. interactive video workflow generation), and many more. Examples of our prior studies include: <a href="/papers/research/Xu2017AnswerBot.pdf" target="_blank">(Xu et al. 2017)</a>, <a href="/papers/research/Liu2018NNGen.pdf" target="_blank">(Liu et al. 2018)</a>, <a href="/papers/research/Sharma2018RecommendingWhoToFollow.pdf" target="_blank">(Sharma et al. 2018)</a>.

### Empirical Studies
We are also interested in bridging the gap between research and practice through empirical studies. They are important to ensure that technologies that we design are relevant to practitioners, address their pain points, and are not evaluated in a biased way. Our work in this area include:
+ We have **mined software repositories to distil insights** about how developers perform certain activities and identify inefficiencies, pain points, and directions for future research. These include studies on: bugs and issues affecting various kinds of systems, activities on and growth of GitHub, factors influencing open source and industrial project quality, developer turnover and retention, and many more. Examples of these studies include: <a href="/papers/research/csmr13.pdf" target="_blank">(Thung et al. 2013)</a>, <a href="/papers/research/emse18-overfitting.pdf" target="_blank">(Le et al. 2018)</a>, <a href="/papers/research/tse19-github.pdf" target="_blank">(Bao et al. 2019)</a>.
+ We have also **analysed bias and limitations that affect existing automated tools**. These include studies that analyse: bias in bug localization data, overfitting in program repair, bias in evaluation of defect prediction studies, and many more. Examples of these studies include: <a href="/papers/research/ase14-bias.pdf" target="_blank">(Kochhar et al. 2014)</a>, <a href="/papers/research/icsme17-jit.pdf" target="_blank">(Huang et al. 2017)</a>, <a href="/papers/research/emse18-overfitting.pdf" target="_blank">(Le et al. 2018)</a>.

