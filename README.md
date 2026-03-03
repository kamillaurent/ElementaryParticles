# ElementaryParticles
This repository contains Blender files with representation of Standard Model elementary particles.

`particles-sorted-logscale.blend` and `Particles_log_scales.blend` has diameter of particles defined as $d_i = log(\frac{m_i}{0.5 m_e}) \, [m]$ , to reconstruct the mass of particle i one can do a simple computation: $ m_i = 0.5 * m_e * 10^{d_i} $

The files `lin_electron--muon.blend` contains particles from electron to muon with diameter defined as $d_i = 0.031 * \frac{m_i}{m_e} \, [m]$