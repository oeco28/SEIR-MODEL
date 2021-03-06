# Description of SEIR-MODEL to try to understand the SARS-CoV-2 epidemic.

This attempt was born out of curiosity of what would be expected for Pullman, WA were I reside. I have since expanded it in collaboration with Ben Kerr. Since then, Mark Tanaka and Carl Bergstrom have also contributed siginficantly to the development of our thoughts.

The pdf document contains an explanation of the choice for the parameter values that we have been using so far and some of the simpler SEIR models we have explored. The references are included in the document.

With the simple model you can already see what the effect of including mortality explicity in the model has on the dynamics, the effect of mitigation 30 days post introduction of the epidemic if transmission is reduced to 2/3 of its original value.

A barebone code for a couple of general cases (not all the scenarios we have looked at is included in the repository). This model was modified to be able to change contact rates for each player individually and the most up to date version of the model can be found at [Ben Kerr's SEIR Risk](https://github.com/evokerr/SEIR_Risk_Model/)

I apologize for any typos, I appreciate any feedback.

An update and cleaner version of this code and explanation for a more general case will be posted sometime soon. We are trying to evaluate other scenarios

I have included the code for examining the effect of mitigation in the structured model as well as examining some scenarios of strong implementation and relaxation of measures in time (mitigation_scenarios.R).

For a network implementation of these models please visit [Ryan McGee's github](https://github.com/ryansmcgee/seirsplus) for a wonderful package in python that facilitates a more realistic investigation of scenarios.

The document "SEIR_covid19_Pullman_v4.pdf" contains specific predictions about Pullman. These were done considering a conservative scenario. For a more risky scenario people can refer to document "SEIR_covid19_Pullman.pdf" (which was the original set of analyses I performed).
