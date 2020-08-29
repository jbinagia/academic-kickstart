+++
title = "On Speeding up Stochastic Simulations by Parallelization of Random Number Generation"
date = 2015-01-01
authors = ["Che-Chi Shu", "Vu Tran", "Jeremy Binagia", "Doraiswami Ramkrishna"]
publication_types = ["2"]
abstract = "This paper adds to the tool kit of stochastic simulations based on a very simple idea. Applicable to both SSA and Tau-leap algorithms, it can notably reduce computational times. Stochastic simulations are based on computing sample paths based on the generation of random numbers with either exactly stipulated distribution functions as in SSA (Gillespie, 1977) or in the method of interval of quiescence (Shah et al., 1977) or distribution functions featuring approximations designed to promote efficiency (as in Tau-leap algorithms (Cao et al., 2006; Tian and Burrage, 2004; Peng et al., 2007; Gillespie, 2001; Ramkrishna et al., 2014) where a leap condition with the parameter epsilon is used). The usual strategy involves sequential computation of a large number of sample paths over a bounded time interval which is covered by a set of discrete time subintervals obtained by random number generation. The strategy here departs from the foregoing by parallelizing the generation of random subintervals for the set of sample paths until all sample paths have been computed for the stated time interval. The advantage of this procedure lies in the fact that the time for initiation of the random number generator has been notably reduced. Many examples are demonstrated from SSA as well as Tau-leap algorithms to establish that the advantage of the approach is much more than conceptual."
featured = false
publication = "*Chemical Engineering Science*"
tags = ["Chemical processes", "Parallel", "Stochastic simulation", "Tau-leap", "stochastic simulation"]
url_pdf = "http://linkinghub.elsevier.com/retrieve/pii/S0009250915004832"
doi = "10.1016/j.ces.2015.06.066"
+++

