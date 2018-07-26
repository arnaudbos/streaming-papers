streaming-papers
================

A curated collection of papers on streaming algorithms

### Please Contribute

If you have papers you want to add, make a pull request. Categories are wide open right now, so just put in a folder that makes sense to you and we'll figure it out.

### Distinct Value Counting

_distinct_value_counting/Probabilistic_Multiplicity_Counting_-_Lieven2010a.pdf_

Known Implementations
* [seiflotfy/pmc](https://github.com/seiflotfy/pmc) - Go
* [sorenmacbeth/runpmc](https://github.com/sorenmacbeth/runpmc) - Clojure

===

#### Data Streams as Random Permutations: the Distinct Element Problem - Helmi, Lumbroso, Martinez, Viola

_distinct_value_counting/data_streams_as_random_permutations.pdf_

Known Implementations:
* [cscotta/recordinality](https://github.com/cscotta/recordinality) - Java

### Distribution Functions

===

#### Dynamic Histograms: Capturing Evolving Data Sets - Donko Donjerkovic, Yannis Ioannidis, Raghu Ramakrishnan

_distribution_functions/dynamic-histograms.pdf_

Known Implementations:
* [bigmlcom/histogram](https://github.com/bigmlcom/histogram) - Clojure
* [bmizerany/perks](https://github.com/bmizerany/perks/blob/histo/histogram/histogram.go) - Go
* [d2fn/shades-rb](https://github.com/d2fn/shades-rb) - Ruby

===

#### The P<sup>2</sup> Algorithm for Dynamic Calculation of Quantiles and Histograms Without Storing Observations - Raj Jain, IMRICH CHLAMTAC

_distribution_functions/psqr.pdf_

Known Implementations:
* [GNU Scientific Library](https://www.gnu.org/software/gsl/doc/html/rstat.html#quantiles) - C
* [scassidy/livestats](https://bitbucket.org/scassidy/livestats) (bitbucket) - Python
* [absmall/p2](https://github.com/absmall/p2) - C++
* [jacksonicson/psquared](https://github.com/jacksonicson/psquared) - java

===

#### Effective Computation of Biased Quantiles over Data Streams: Cormode, Korn, Muthukrishnan, Srivastava

_distribution_functions/bquant.pdf_

Known Implementations:
* [bmizerany/perks](https://github.com/bmizerany/perks/blob/histo/quantile/stream.go) - Go

===

### Summary Statistics

#### Formulas for Robust, One-Pass Parallel Computation of Covariances and Arbitrary-Order Statistical Moments - Pilippe Pebay

_Summary Statistics/one_pass_moments_Pebay.pdf_

Known Implementations:
[Kitware/VTK](https://github.com/Kitware/VTK/) (mirror) - C++ (check in [filters/statistics/vtkStatisticsAlgorithm.h](https://github.com/Kitware/VTK/blob/master/Filters/Statistics/vtkStatisticsAlgorithm.h))
