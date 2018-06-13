# WEBPAGE STILL UNDER CONSTRUCTION!!! WILL BE UP SOON. 
# Machine Learning Aided Discovery of Ultrahigh Capacitive Energy Storage Materials

Course: EECS 349 Machine Learning, Professor Doug Downey, Spring 2018, Northwestern University

Team members: Benjamin Warren (Junior, Materials Science/Computer Science)

Contact: benjaminwarren2019@u.northwestern.edu

## Abstract
Ultracapacitors are an emerging class of electronic materials that hold major interest due to their applications in wide-ranging technologies from renewable energies to rail guns. Present high capacitance materials are effective, yet there remain thousands of experimentally uninvestigated material systems with potential for ultrahigh capacitive applications. Reliable high-throughput methods for identifying promising high energy storage materials promise to greatly accelerate the search for better energy materials.

As proof-of-concept, we pull dielectric materials data from Citrination and other databases. Various machine learning regression models are trained on 23 electronic property features to predict a “figure of merit”, FOM = κE<sub>g</sub><sup>2</sup>, proportional to the dielectric energy storage density. We find the most reliable model with a RandomForest learner, which gives correlation coefficient = 0.5703 and relative absolute error = 71.85%. Evaluation against a test set of procedurally generated novel materials suggests NaTaF<sub>3</sub>, NaNbF<sub>3</sub>, and NaHfO<sub>3</sub> as good candidates for experimental evaluation. We conclude by discussing lessons from the machine learning and outlining a multi-tiered computational approach for materials discovery.

## Motivation
