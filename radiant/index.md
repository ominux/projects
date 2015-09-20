---
layout: default
---

RADIANT: Rapid Development and Distribution of Statistical Tools for High-Throughput Sequencing Data
====================================================================================================

Overview
--------

RADIANT is a research project funded by the 7th Framework Programme of
the European Commission.The project started in December 2012 and brings
together ten project partners from five European countries.

The aim of the RADIANT project is to develop new statistical analysis
tools for solving open problems in high-throughput sequencing (HTS) data
analysis. HTS is a rapidly evolving family of technologies with many
applications, including genetics of both rare and common diseases,
understanding disease mechanism progression. RADIANT aims to provide an
integrated computational framework for HTS data analysis that is robust
and user-friendly, and provide tools to benchmark experimental protocols
and statistical methods. The project will establish training materials
and an extensive training programme for the rapid dissemination of these
new tools to the biomedical community.

The project is sponsored by [EU FP7-HEALTH Project Ref 305626 "Rapid development and distribution of statistical tools for high-throughput sequencing data"](http://cordis.europa.eu/projects/rcn/105701_en.html) and is a collaboration with [Magnus Rattray](http://www.ls.manchester.ac.uk/people/profile/?personid=10584) of University of Manchester, [Korbinian Grote](http://radiant-project.eu/Consortium/Partners/Genomatix.html) of Genomatix Software GmbH Germany, [Alessandro Guffanti](http://radiant-project.eu/Consortium/Partners/Genomnia.html) of Genomia Italy, [Wolfgang Huber](http://radiant-project.eu/Consortium/Partners/EMBL.html) of EMBL Heidelberg, [Diego di Bernardo](http://dibernardo.tigem.it/wiki/index.php/Main_Page) of Fondazione Telethon, [Mattia Pelizzola](http://radiant-project.eu/Consortium/Partners/IIT.html) of Istituto Italiano di Tecnologia, [Jean-Philippe Vert](http://radiant-project.eu/Consortium/Partners/ARMINES.html) of ARMINES France, [Klaus Mauch](http://www.insilico-biotechnology.com/people) of Insilico Biotechnology, [Jean-Marie Mouillon](http://www.fluxome.com/company/organization/leadership-team.aspx) of Fluxome Sciences A/S, [Mark Robinson](http://radiant-project.eu/Consortium/Partners/Zurich.html) of University of Zurich Switzerland and [Simon Tavare](http://radiant-project.eu/Consortium/Partners/CAM.html) of University of Cambridge.

Personnel at Sheffield
----------------------

- [Zhenwen Dai](http://www.dcs.sheffield.ac.uk/cgi-bin/makeperson?Z.Dai), post-doctoral research assistant
- [Teo de Campos](http://www.dcs.sheffield.ac.uk/cgi-bin/makeperson?T.deCampos), post-doctoral research assistant
- [James Hensman](http://www.dcs.sheffield.ac.uk/cgi-bin/makeperson?J.Hensman), MRC Fellow

Publications
------------

The following publications have provided background to our work in this
project.

### Conference Papers

<span class="author">J. Hensman, M. Zwiessele and N. D. Lawrence.
</span> (2014) <span class="papertitle">"Tilted variational
Bayes"</span> in S. Kaski and J. Corander (eds) <span
class="journal">Proceedings of the Seventeenth International Workshop on
Artificial Intelligence and Statistics</span>, JMLR W&CP 33, Iceland, pp
. \[[Software](https://github.com/SheffieldML/GPy%20)\]\[[Google Scholar
Search](http://scholar.google.com/scholar?hl-en&lr=&q=Tilted+Variational+Bayes+&btnG=Search)\]

#### Abstract

We present a novel method for approximate inference. Using some of the
constructs from expectation propagation (EP), we derive a lower bound of
the marginal likelihood in a similar fashion to variational Bayes (VB).
The method combines some of the benefits of VB and EP: it can be used
with light-tailed likelihoods (where traditional VB fails), and it
provides a lower bound on the marginal likelihood. We apply the method
to Gaussian process classification, a situation where the
Kullback-Leibler divergence minimized in traditional VB can be infinite,
and to robust Gaussian process regression, where the inference process
is dramatically simplified in comparison to EP.

Code to reproduce all the experiments can be found at
[github.com/SheffieldML/TVB](github.com/SheffieldML/TVB).

<span class="author">R. Andrade-Pacheco, J. Hensman and N. D. Lawrence.
</span> (2014) <span class="papertitle">"Hybrid
discriminative-generative approaches with Gaussian processes"</span> in
S. Kaski and J. Corander (eds) <span class="journal">Proceedings of the
Seventeenth International Workshop on Artificial Intelligence and
Statistics</span>, JMLR W&CP 33, Iceland, pp .
\[[Software](https://github.com/SheffieldML/GPy%20)\]\[[Google Scholar
Search](http://scholar.google.com/scholar?hl-en&lr=&q=Hybrid+Discriminative-Generative+Approaches+with+Gaussian+Processes+&btnG=Search)\]

#### Abstract

Machine learning practitioners are often faced with a choice between a
discriminative and a generative approach to modelling. Here, we present
a model based on a hybrid approach that breaks down some of the barriers
between the discriminative and generative points of view, allowing
continuous dimensionality reduction of hybrid discrete-continous data,
discriminative classification with missing inputs and manifold learning
informed by class labels.

### Related References

<span class="author">J. Hensman, N. D. Lawrence and M. Rattray. </span>
(2013) <span class="papertitle">"Hierarchical Bayesian modelling of gene
expression time series across irregularly sampled replicates and
clusters"</span> in <span class="journal">BMC Bioinformatics</span> 14
(252) \[[DOI](http://dx.doi.org/doi:10.1186/1471-2105-14-252)\]\[[Google
Scholar
Search](http://scholar.google.com/scholar?hl-en&lr=&q=Hierarchical+Bayesian+modelling+of+gene+expression+time+series+across+irregularly+sampled+replicates+and+clusters+&btnG=Search)\]

#### Abstract

**Background**

Time course data from microarrays and high-throughput sequencing
experiments require simple, computationally efficient and powerful
statistical models to extract meaningful biological signal, and for
tasks such as data fusion and clustering. Existing methodologies fail to
capture either the temporal or replicated nature of the experiments, and
often impose constraints on the data collection process, such as
regularly spaced samples, or similar sampling schema across
replications.

**Results**

We propose hierarchical Gaussian processes as a general model of gene
expression time-series, with application to a variety of problems. In
particular, we illustrate the method's capacity for missing data
imputation, data fusion and clustering.The method can impute data which
is missing both systematically and at random: in a hold-out test on real
data, performance is significantly better than commonly used imputation
methods. The method's ability to model inter- and intra-cluster variance
leads to more biologically meaningful clusters. The approach removes the
necessity for evenly spaced samples, an advantage illustrated on a
developmental Drosophila dataset with irregular replications.

**Conclusion**

The hierarchical Gaussian process model provides an excellent
statistical basis for several gene-expression time-series tasks. It has
only a few additional parameters over a regular GP, has negligible
additional complexity, is easily implemented and can be integrated into
several existing algorithms. Our experiments were implemented in python,
and are available from the authors' website:
<http://staffwww.dcs.shef.ac.uk/people/J.Hensman/>.

<span class="author">N. Fusi, C. Lippert, K. Borgwardt, N. D. Lawrence
and O. Stegle. </span> (2013) <span class="papertitle">"Detecting
regulatory gene-environment interactions with unmeasured environmental
factors"</span> in <span class="journal">Bioinformatics</span>
\[[DOI](http://dx.doi.org/10.1093/bioinformatics/btt148)\]\[[Google
Scholar
Search](http://scholar.google.com/scholar?hl-en&lr=&q=Detecting+Regulatory+Gene-Environment+Interactions+with+Unmeasured+Environmental+Factors+&btnG=Search)\]

#### Abstract

**Motivation**: Genomic studies have revealed a substantial
heritable component of the transcriptional state of the cell. To fully
understand the genetic regulation of gene expression variability, it is
important to study the effect of genotype in the context of external
factors such as alternative environmental conditions. In model systems,
explicit environmental perturbations have been considered for this
purpose, allowing to directly test for environment-specific genetic
effects. However, such experiments are limited to species that can be
profiled in controlled environments, hampering their use in important
systems such as human. Moreover, even in seemingly tightly regulated
experimental conditions, subtle environmental perturbations cannot be
ruled out, and hence unknown environmental influences are frequent.
Here, we propose a model-based approach to simultaneously infer
unmeasured environmental factors from gene expression profiles and use
them in genetic analyses, identifying environment-specific associations
between polymorphic loci and individual gene expression traits.

**Results**: In extensive simulation studies, we show that our
method is able to accurately reconstruct environmental factors and their
interactions with genotype in a variety of settings. We further
illustrate the use of our model in a real-world dataset in which one
environmental factor has been explicitly experimentally controlled. Our
method is able to accurately reconstruct the true underlying
environmental factor even if it's not given as an input, allowing to
detect genuine genotype-environment interactions. In addition to the
known environmental factor, we find unmeasured factors involved in novel
genotype-environment interactions. Our results suggest that interactions
with both known and unknown environmental factors significantly
contribute to gene expression variability.

**Availability**: Software available at
<http://ml.sheffield.ac.uk/qtl/limmi>

**Contact**: [oliver.stegle@ebi.ac.uk](oliver.stegle@ebi.ac.uk),
[nicolo.fusi@sheffield.ac.uk](nicolo.fusi@sheffield.ac.uk)

<span class="author">J. Hensman, M. Rattray and N. D. Lawrence. </span>
(2012) <span class="papertitle">"Fast variational inference in the
conjugate exponential family"</span> in P. L. Bartlett, F. C. N.
Pereira, C. J. C. Burges, L éo. Bottou and K. Q. Weinberger (eds) <span
class="journal">Advances in Neural Information Processing
Systems</span>, .
\[[PDF](http://books.nips.cc/papers/files/nips25/NIPS2012_1314.pdf)\]\[[Google
Scholar
Search](http://scholar.google.com/scholar?hl-en&lr=&q=Fast+variational+inference+in+the+Conjugate+Exponential+family+&btnG=Search)\]

<span class="author">J. Hensman, N. Fusi and N. D. Lawrence. </span>
(2013) <span class="papertitle">"Gaussian processes for big data"</span>
in A. Nicholson and P. Smyth (eds) <span class="journal">Uncertainty in
Artificial Intelligence</span>, AUAI Press, .
\[[PDF](http://auai.org/uai2013/prints/papers/244.pdf)\]\[[Google
Scholar
Search](http://scholar.google.com/scholar?hl-en&lr=&q=Gaussian+Processes+for+Big+Data+&btnG=Search)\]

<span class="author">N. Fusi, O. Stegle and N. D. Lawrence. </span>
(2012) <span class="papertitle">"Joint modelling of confounding factors
and prominent genetic regulators provides increased accuracy in
genetical genomics studies"</span> in <span class="journal">PLoS
Computat Biol</span> 8, pp e1002330
\[[Software](http://ml.sheffield.ac.uk/qtl/%20)\]\[[PDF](http://www.ploscompbiol.org/article/info%3Adoi%2F10.1371%2Fjournal.pcbi.1002330)\]\[[DOI](http://dx.doi.org/10.1371/journal.pcbi.1002330)\]\[[Google
Scholar
Search](http://scholar.google.com/scholar?hl-en&lr=&q=Joint+Modelling+of+Confounding+Factors+and+Prominent+Genetic+Regulators+Provides+Increased+Accuracy+in+Genetical+Genomics+Studies+&btnG=Search)\]

#### Abstract

Expression quantitative trait loci (eQTL) studies are an integral tool
to investigate the genetic component of gene expression variation. A
major challenge in the analysis of such studies are hidden confounding
factors, such as unobserved covariates or unknown subtle environmental
perturbations. These factors can induce a pronounced artifactual
correlation structure in the expression profiles, which may create
spurious false associations or mask real genetic association signals.
Here, we report PANAMA (Probabilistic ANAlysis of genoMic dAta), a novel
probabilistic model to account for confounding factors within an eQTL
analysis. In contrast to previous methods, PANAMA learns hidden factors
jointly with the effect of prominent genetic regulators. As a result,
this new model can more accurately distinguish true genetic association
signals from confounding variation. We applied our model and compared it
to existing methods on different datasets and biological systems. PANAMA
consistently performs better than alternative methods, and finds in
particular substantially more trans regulators. Importantly, our
approach not only identifies a greater number of associations, but also
yields hits that are biologically more plausible and can be better
reproduced between independent studies. A software implementation of
PANAMA is freely available online at <http://ml.sheffield.ac.uk/qtl/>.
