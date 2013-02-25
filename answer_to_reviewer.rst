We would like thank the reviewers for their careful reading of the
manuscript and their suggestions that helped us improve the manuscript.
We have address the different comments. The major changes in the
manuscript have been highlighted in purple with a triangle in the margin
on the left.

Reviewer 1
============

  **It would be good to start the introduction with a definition of functional connectivity.**

Indeed, we added two lines at the beginning of the paragraph on the
bottom of page 1.

  **It would make sense to discuss in this context recent developments in very rapid acquisition protocols as they prevent aliasing and can be used to better regress out physiological confounds, e.g.:**

  **1.	Boyacioglu R, Barth M. Generalized iNverse imaging (GIN): Ultrafast fMRI with physiological noise correction. Magnetic Resonance Medicine. 2012**

We thank the reviewer for this suggestion. We have added a note about
these developments on the middle of the second column of page 2.

  **Related to "separate out overlapping spatial maps that capture functional networks":  This is somewhat incongruent with a previous statement: "care must be taken not to define too many regions that would overlap and lead to mixing of the signal." Please clarify.**

We hope that we have clarified, please consult the bottom of the first
column, page 3.

  **Why not refer to the "inverse covariance matrix" as "precision matrix" throughout?**

We would rather avoid using this term that is technical and may confuse
the reader. We have however added a reference to it (page 5, top of first
column).

  **please refer to the following relevant papers:**

    **Shows how to use graph-topological metrics together with
    decoding:**

    **1.	Ekman M, Derrfuss J, Tittgemeyer M, Fiebach CJ. Predicting errors from reconfiguration patterns in human brain networks. PNAS. 2012 Oct 9;109(41):16714-9.**

We have added a reference (bottom of second column, page 7).

   **I would appreciate a reference which supports the following statement in footnote 8: "This is to be contrasted to Bayesian model comparison, which will give correct results only if the true generative model is in the list of models compared."**

We have reformulated the corresponding remark (footnote bottom of page 8
and 9), to give a better explaination, with references.

We thank the reviewer for pointing out many typos and misformulations,
that have we corrected.

Reviewer 2
============

  **1.	While the focus of this review is resting-state connectivity, it
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
  connectome inference.**

We thank the review for these suggestions. We have expended the paragraph
on these issues (page 4, bottom of first column). However, we do not
wish to discuss PPI or DCM, as they are a bit on the side of the scope of
the review and we do not have first-hand experience with these methods.

  **2.	I agree with most of the sentiments that have been
  discussed with respect to node definition (i.e. regional
  parcellation). However, I am dubious about the notion of an "optimal"
  parcellation template and associated number of regions. The
  connectome is an inherently multi-scale and hierarchical entity, and
  the appropriate parcellation granularity largely depends on the
  application at hand. Sporns labours this point insistently in his
  book. Furthermore, voxel scale mapping can be problematic due to
  spurious short-range correlations between neighbouring voxels that
  are induced by smoothing effects. As such, it is not clear why
  reproducing voxel mapping is a relevant criterion. Finally, perhaps
  consideration should be given to reviewing the randomised
  parcellation methods that underscored some of the first attempts to
  map connectomes (e.g. Hagmann, 2008, Mapping the structural core of
  the human cerebral cortex; Zalesky, 2010, Does the choice of nodes
  matter?). I accept that randomised parcellations were originally used
  for mapping the structural connectome, but they have been utilised in
  functional connectomics and have the benefit of ensuring nodes are
  spatially compact (surface area to volume ratio maximised) and yield
  more uniform SNR across nodes (due to uniformity in node volume).**

We agree with the review that multiple scales are necessary to describe
functional connectivity. We have added remarks on this, on page 3,
bottom of second column. Similarly, we think that randomized
parcellations are a good idea, and have mentionned them in the above
remarks.

  **3.	I agree with the transitivity example (variables a, b and c)
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
  (e.g. Ferguson et al, 2012)?**

We agree that the best approaches to perform structure recovery are still
open questions, however based on our personnal experience (a lot being
unpublished, but Varoquaux 2012 compares a variety of estimators), the
sparse penalization approaches give a very good compromise, and with good
implementations their computational cost is not a major problem. Cholesky
decomposition requires the choice of an ordering in the nodes of the
graph, which ultimately corresponds to imposing a DAG (directed acyclic
graph) structure on brain connectivity. This is not at all compatible
with our knowledge of brain functional organization.

    **4.	 In regards to the description of the network-based statistic
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
    Zalesky et al 2012, Connectivity differences in brain networks).**

Indeed, we have corrected our description of NBS (page 6, middle of
second column).

   **1.	Using "the connectome" is probably a misnomer, particularly in
   the context of functional connectomics. Functional connectomes can
   differ vastly depending on the technique used to infer edge
   connectivity, which is a detail this article has demonstrated very
   clearly. Perhaps "the connectome" is a term that should be reserved
   for structural connectomics.** 

We have added a last sentence in the conclusion regarding this point.

We thank the reviewer for bringing to our attention typos and
misformulations. We have addressed them in our revised version.
