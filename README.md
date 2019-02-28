# GPII Matchmaker Evaluation

Data and tools for evaluating the [GPII matchmakers](http://wiki.gpii.net/w/Matchmaking) 
developed in the [Cloud4all project](https://cordis.europa.eu/project/rcn/101353/factsheet/en),
more specfically the third evaluation phase ("third pilot"). 

Data originally created by [Cloud4allTUD](https://github.com/claudialoitsch/)
and further adapted here.

Background: 
* [GPII JIRA ticket 1132](http://issues.gpii.net/browse/GPII-1132).
* [Profile Matching Technical Concept](http://www.cloud4all.info/research/public-deliverables/d204-1-profile-matching-technical-concept/) 
(Cloud4all deliverable D204.1, October 2012).
* [Matchmaking algorithms and their evaluation](http://www.cloud4all.info/research/public-deliverables/d204-3-matchmaking-algorithms-and-their-evaluation-2/)
(Cloud4all deliverable D204.3, updated April 2015).
* [Pilots evaluation framework, experimental plan and logistics V3](http://www.cloud4all.info/research/public-deliverables/d402-2-3-pilots-evaluation-framework-experimental-plan-and-logistics-v3/) 
(Cloud4all deliverable D402.2.3, October 2014).

This repository has three directories:
* `testdata` contains the payloads that were sent to the matchmakers;
* `pilot3_rbmm` contains the settings inferred by the Rule-Based Matchmaker;
* `pilot3_stmm` contains the settings inferred by the Statistical Matchmaker.

To test the Statistical Matchmaker with the payloads in the `testdata` directory, see the [instructions for running the Statistical Matchmaker](https://github.com/REMEXLabs/GPII-Statistical-Matchmaker#testing-the-statistical-matchmaker). 

## Funding Acknowledgement

The research leading to these results has received funding from the European
Union's Seventh Framework Programme (FP7/2007-2013) under grant agreement No.289016
(Cloud4all).

