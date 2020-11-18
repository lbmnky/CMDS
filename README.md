# CMDS
v0.2

Simulate coherent multidimensional spectroscopy signals using from quantum mechanical models.

## Introduction

The code relies primarily on [qojulia/QuantumOptics.jl](https://github.com/qojulia/QuantumOptics.jl). The module [CMDS.jl](/cmds.jl) contains all the necessary functions. [examples/](/examples) shows example scenarios.

## Installation

CMDS requires the Julia language and [qojulia/QuantumOptics.jl](https://github.com/qojulia/QuantumOptics.jl), which can be installed from via the standard sources:

[Julia](https://docs.julialang.org/en/v1/manual/getting-started/)


[QoJulia](https://docs.qojulia.org/installation/)


## Examples

The following [/examples](/examples) are available.

### coupled_dimer.jl

The properties (angles, coupling strength, etc.) of a coupled dimer system are calculated and QuantumOptics.jl is used to calculate the correlation function and linear absorption spectrum.

![coupledDimer](/example_images/coupledDimer.png)

CMDS.jl uses QuantumOptics.jl to calculate the response functions in a four-wave mixing experiment and calculates the expected 2D spectrum.

![coupledDimer 2D spectrum](/example_images/coupledDimer2D.png)

### displaced_harmonic_oscillator_model.jl

[text]

![displacedHarmonicOscillator](/example_images/displHarmOsc.png)

2D spectrum of the Jaynes-Cummings model at different delays of the population time T.

![displacedHarmonicOscillator 2D spectrum](/example_images/displHarmOsc2D.png)

### FCF_morse-potential.jl

[text]

![FCF Morse Potential](/example_images/FCfactorsMorsePot.png)

### Jaynes-Cummings model

[text]

![Jaynes-Cummings](/example_images/JaynesCummingsSpectrum.png)

![Jaynes-Cummings 2D spectrum](/example_images/JaynesCummingsSpectrum2D.png)


### Tavis-Cummings

In order to go beyond the Jaynes-Cummings model ...
