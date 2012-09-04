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

Tentative outline
===================

 Comparing Connectomes Between Populations

 1. estimating connectome
    a. defining regions
    b. estimating connections
 2. Comparing connections
    a. mass univariate
    b. more rational methods?
 3. Comparing Network Statistics
 4. Predictive Modelling
 5. Functional and Effective
    a. Link w/ SEM
    b. Diatribe

Some ref
==========

    Marralec - partial correlation to SEM - a theoretical investigation of the
r elationship between structural equation modeling and partial correlation in
functional MRI e ffective connectivity computational intelligenecns and
Neuroscience

