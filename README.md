# Elementary Particles
This repository contains Blender files with representation of Standard Model elementary particles.

## Logaritmic Mass Dependence

The files `particles-sorted-logscale.blend` and `Particles_log_scales.blend` contains particles with diameters defined as

$d_i = log(\frac{m_i}{0.5 m_e})$ [m],

where $d_i$ and $m_i$ are the diameter and mass of the i-th particle. To reconstruct the mass of i-th particle one can do a simple computation: 

$m_i = 0.5  m_e  10^{d_i}$ [GeV].

## Linear Mass Dependence
Since there are around 5 orders of magnitude from electron mass to top mass, we cannot put the linear dependence alltogether in one Blender file, otherwise it craches. We split the linear dependence of particle masses in 3 files:

The file `lin_electron--muon.blend` contains particles from electron to muon with diameter defined as $d_i = 0.031  \frac{m_i}{m_e} \, [m]$