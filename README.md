CLgrep
======

CLgrep, a GPU-armed string matching tool.
Currently it sitll under development.

Soon it is going to be most awesome exact string matching tool.
You need to make sure that you have install OpenCL implementation.

CLgrep is developed without any extension, and therefore it should be able to
run with any OpenCL implementation but AMD APP SDK is suggested.


Thesis Abstract
In this study, we widely investigate the problem of string matching in the context of Heterogeneous Parallel Computing. A overview of string matching is made, in which the different forms of string matching problem are distinguished, and the classifications of string matching algorithm are discussed. 

As an alternative to grep for computational intensive string matching and in addition to support the research of the study, a parallel exact string matching utility `Clgrep' is developed. 

By experimental studies, we investigate the use of heuristics-based algorithms, specifically QS and Horspool algorithms, in the context of Heterogeneous Parallel Computing. The results suggest that the performance of Heterogeneous Parallel Computing matching, either on multi-core CPU or GPU, is highly related to the computational intensity of certain cases. When computational power is intensively required, the SIMD Parallel Computing model of Clgrep can be several times more efficient than corresponding sequential matching program.
