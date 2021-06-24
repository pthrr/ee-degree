## Section 1: White magic
- briefly understand how current, voltage and impedance are only lumped properties of electromagnetic fields in free space
- learn to calculate voltage and current at every node/branch of linear electrical networks consisting of complex impedances based on the differential equation of the system
- understand the concept of sources/sinks, phasors, efficiency/power transfer, Q factor/resonance, superposition, dispersion and the concept of equivalent circuits
- use NGSPICE to validate

## Section 2: Black magic
- derive the equivalent circuit for a transmission line and the telegraphers equations
- derive all results from the solution of the telegraphers equations like primary/secondary line parameters
- derive approximations for phase velocity, input impedance and characteristic impedance over frequency and reflection coefficient
- understand basic assumptions and their consequences like anisotropy, symmetry, homogenity and odd/even mode properties for differential transmission systems
- thouroughly understand laplace transform mathematically and its relation to the fourier transform: fourier spectrum, uncertainty principle, periodicity and windowing; See how the Fourier transform can be used to overcome those cumbersome differential equations methods (AC-calculus)
- understand black box behavioural models like S/h/Z/Y/T/ABCD-parameters and their transformations. What are their respective advantages? What information are they missing? How will reciprocity, symmetry, passivity influence these models? Learn matrices for common components!
- build a PCB on CNC machine that decouples transmission lines for single-ended measurements with VNA. What would an optimal/practical design look like?
- design a twisted-pair transmission line setup, derive its characteristic impedance from its geometry, measure S-parameters and calculate line parameters via T-parameters
- terminate the twisted-pair at each end with its characteristic impedance, create stubs with high-impedance terminations, use the theory of first reflections and mathematical optimization to build a resistive power divider that minimizes the reflection factor at the star points of the high-impedance stubs

## Section 3:
- implement a non-standard FDTD scheme to solve your transmission line setup and compare to your measurement in time and frequency domain
- implement a Particle Swarm Optimization (PSO) and fit the frequency response of your simulation onto your measurement. What epislon_r and tan_d do the cables have? Does Kramer-Kronig hold?
- measure the length of the cables through their impulse response (IR)

## Section 4: Going multi-dimensional
- Radar
- build MIMO out of single units with single antennas
