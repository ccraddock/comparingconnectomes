Focus on the comparison of functional-connectivity graphs

Topics to adress
==================

* Partial correlation/inverse covariance estimator

* Comparison across subject

* SEM and link to correlation analysis

* Integration mesures

* Predictive modelling

* Remark on functional vs effective connectivity:

    - Refs: debate after functional connectivity workshop

Notes from the chat
========================

* Cameron: using 200 parcellations of the brain
  
  I train a SVR for each parcellation, using all of the brain that is
  outside of the ROI

  i can then apply that "network model" to independent data to predict a
  time course of the ROI
    
  i have been working on relating the resulting measure of prediction
  accuracy to "integration" a la marrelec
   
  me: I like that model by the way
     
     It should go in our review

Misc
=====


Gael: some remarks that came to me during the HBM morning workshop on
brain graphs:

* Check Zaleski's statement that partial correlation underestimate the
  clustering coefficient using a decent estimator (in their 2012 paper)

* Check that the hypothesis underlying the network-based statistics
  actually hold by doing a proper permutation test

