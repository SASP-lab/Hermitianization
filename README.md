# Stochastic response determination of nonlinear oscillators via operatorial dynamics: an approach based on stochastic averaging and adiabatic elimination

Repository to reproduce the paper results.

## Abstract

This paper presents a methodology based on the spectral decomposition of Hermitian operators as an accurate tool for accelerating the spectral expansion of the response probability density function (PDF) of lightly damped and overdamped nonlinear oscillators. This framework relies on the reduction of the stochastic dimensions of such systems through stochastic averaging and adiabatic elimination. However, these techniques yield Fokker-Planck equations governed by non-Hermitian operators with complex-valued eigenvalues, which influence the orthogonality and instability of spectral representations. To address this problem, Lamperti and similarity transformations are employed to construct an equivalent Schrödinger-like Hermitian operator governing the evolution of the system response PDF in a transformed space. This approach also enables the transformation of the obtained PDF back to its original space in an efficient manner. Among the indicative examples included in this paper, a lightly damped Duffing oscillator is first treated with energy-based stochastic averaging to determine a reduced-order model governing the dynamics of the energy envelope and displacement amplitude. Furthermore, a single-degree-of-freedom oscillator with asymmetric bistable nonlinearity and a multi-degree-of-freedom oscillator modeling the behavior of a nonlinear weakly coupled tuning fork resonator, in an overdamped regime, are treated with adiabatic elimination. The numerical results demonstrate that the present methodology shows excellent agreement when compared with the response extracted from Monte Carlo simulation data. Moreover, the spectral decomposition of the discretized Hamiltonian enabled a detailed analysis of the influence of eigenmodes on the shape of both transient and stationary phases of the system response PDF.

## Install the necessary packages

``pip install numpy scipy matplotlib pickle``

Also install LaTeX to visualize the graphs, otherwise disable it with ``plt.rcParams['text.usetex'] = False``.