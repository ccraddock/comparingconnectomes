To facilitate the electronic publication of your manuscript (should it be accepted), we request that your manuscript text, tables and figure legend be submitted in an editable format (Word or LaTex only), and all figures uploaded individually as TIF or EPS files.

Reviewer #1
===========

Page 1:

It would be good to start the introduction with a definition of functional connectivity.

Section 2.2

Related to "separate out overlapping spatial maps that capture functional networks":  This is somewhat incongruent with a previous statement: "care must be taken not to define too many regions that would overlap and lead to mixing of the signal." Please clarify.


Reviewer #2:
============

Minor remarks
--------------

1.	While the focus of this review is resting-state connectivity, it
is reiterated throughout the article that the connectivity techniques
discussed are also relevant to task-based inference. This assertion may
require some clarification, since inferring context-specific connectivity
introduces several new challenges; namely, the difficulty in
disambiguating task-specific connectivity effects from intrinsic
connectivity mediated by shared neuromodulatory/task inputs, anatomical
pathways, etc. The brief mention of beta-series regression is relevant in
this regard. An alternative is PPI and very recent work has demonstrated
the utility of DCM (e.g. Seghier et al, 2013). Perhaps consideration can
be given to briefly flagging the issues that are unique to task-based
connectome inference.  

2.	I agree with most of the sentiments that have been discussed with
respect to node definition (i.e. regional parcellation). However, I am
dubious about the notion of an "optimal" parcellation template and
associated number of regions. The connectome is an inherently multi-scale
and hierarchical entity, and the appropriate parcellation granularity
largely depends on the application at hand. Sporns labours this point
insistently in his book. Furthermore, voxel scale mapping can be
problematic due to spurious short-range correlations between neighbouring
voxels that are induced by smoothing effects. As such, it is not clear
why reproducing voxel mapping is a relevant criterion. Finally, perhaps
consideration should be given to reviewing the randomised parcellation
methods that underscored some of the first attempts to map connectomes
(e.g. Hagmann, 2008, Mapping the structural core of the human cerebral
cortex; Zalesky, 2010, Does the choice of nodes matter?). I accept that
randomised parcellations were originally used for mapping the structural
connectome, but they have been utilised in functional connectomics and
have the benefit of ensuring nodes are spatially compact (surface area to
volume ratio maximised) and yield more uniform SNR across nodes (due to
uniformity in node volume).

3.	I agree with the transitivity example (variables a, b and c)
given to illustrate the shortcoming of using the sample correlation to
infer pairwise connectivity. This is an important point. The problem with
partial correlation, however, is its greater susceptibility to noise, and
more importantly, partial correlation tends to break open both spurious
and genuine triangles (i.e. transitive closures), leading to
underestimation of the connectome's true clustering coefficient. For
examples, see Zalesky et al. 2012 (on the use of correlation.). This
might not have been apparent in Smith et al, 2011 (Network modelling
methods) because the topologies simulated therein did not contain any
triangles and the subsequent Ramsey et al 2011 work deleted all closures
in a post hoc step. Finally, I agree that LASSO and other sparse
regression approaches are very promising, but the difficulty here is the
added computational burden and the choice of parameters. Also, what about
discussing Cholesky decomposition with regards to structure recovery
(e.g. Ferguson et al, 2012)?

4.	 In regards to the description of the network-based statistic
(NBS), rather than saying "whole network is likely to carry an effect",
it may be more accurate to write a "cluster of connections shows an
effect" or a "sub-network comprising a group of connections shows an
effect". The NBS doesn't need the effect to span the whole network. In
fact the NBS can declare an effect at a single connection. Also, it might
be worth mentioning that the NBS specifically addresses the massive
multiple comparisons problem associated with edge-wise mass univariate
testing on the connectome. Finally, consideration can be given to briefly
reviewing related approaches for statistically comparing the connectome,
such as spatial pairwise clustering (e.g. Hipp et al, 2011, Oscillatory
synchronization in large scale cortical networks predicts perception;
Zalesky et al 2012, Connectivity differences in brain networks). 

Trivial points
==============

1.	Using "the connectome" is probably a misnomer, particularly in
the context of functional connectomics. Functional connectomes can differ
vastly depending on the technique used to infer edge connectivity, which
is a detail this article has demonstrated very clearly. Perhaps "the
connectome" is a term that should be reserved for structural
connectomics. 


