# TwoLoopFV
This Mathematica library is published with the paper (....). It includes the result of the hidden-region contribution to the asymptotic behaviour of 2 to 3 scattering amplitudes in {\cal N}=4 super-Yang-Mills theory at two loops in the limit where final-state parton 3 is collinear to initial-state parton 2.    

The files "DPHiddenRegion.mx" and "HBHiddenRegion.mx" contain the result of the computation of the hidden region of the Double Pentagon and Hexagon Box topologies, respectively. 
In the notebook "TwoLoopHiddenRegion.nb", we assemble and present the hidden region of the amplitude in the trace basis (see eq.(3.5)-eq.(3.6) of https://arxiv.org/pdf/2003.03120), and their $x$ and $y$ dependence decomposed in both the trace basis and the t-channel colour-flow basis given in the appendix B.4 of https://arxiv.org/pdf/2412.20578. 

In the t-channel basis we also check that the entire dependence on non-collinear parts (i.e. the complete dependence on $x$ and $y$) in the two-loop splitting amplitude $\mathbf{Sp}^{(2)}$ is captured by the hidden region. 

# Usage
To run the Mathematica notebook "TwoLoopHiddenRegion.nb", the package "PolyLogTools"(https://arxiv.org/pdf/1904.07279) should be installed. 
Please put the file "Amp5ptTchannel.mx", "DPHiddenRegion.mx", "HBHiddenRegion.mx", "DeltaTimesAmp4pt.mx" and "Amplitude2L.txt" in the same directory as that of the notebook.

