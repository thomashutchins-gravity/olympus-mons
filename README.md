# Olympus M.O.N.S

Olympus M.O.N.S (Mountains On Neutron Stars) is a numerical code that calculates the size of neutron
star mountains; it performs 1D simulations of the hydrostatic and thermal structure of accreting 
neutron stars.

## Scientific background and motivation

The spin frequencies of neutron stars in low-mass X-ray binaries (LMXBs) appear to be well below that
of the Keplerian break-up spin frequency. One possible explanation for this, despite the existence of
accretion spin-up torques, is the emission of gravitational waves from the star. This code models
gravitational wave emission in the following way:

- **Temperature asymmetries:** anisotropic heat transport produces temperature gradients inside the
  star.
- **Crustal lattice pressure:** temperature asymmetries induce perturbations in the pressure of the
  crystalline structure that makes up the star's solid crust.
- **Mass asymmetry:** pressure perturbations lead to an elastic readjustment of the crustal matter,
  giving the star a non-zero mass quadrupole moment.

Such a mass asymmetry, or a "mountain", would then lead the star to radiate gravitationally as it 
spins/rotates.

## Publications

The code underpins the following papers. If you use it, please cite the first paper, which is also
the one given in [`CITATION.cff`](CITATION.cff).

1. T. J. Hutchins and D. I. Jones, *Numerical calculations of neutron star mountains supported by
   crustal lattice pressure*, MNRAS (accepted), [arXiv:2603.28857](https://doi.org/10.48550/arXiv.2603.28857).
2. D. I. Jones and T. J. Hutchins, *Crustal lattice pressure as a source of neutron star mountains*,
   MNRAS **540**, 2349 (2025), [doi:10.1093/mnras/staf784](https://doi.org/10.1093/mnras/staf784).
3. T. J. Hutchins and D. I. Jones, *Gravitational radiation from thermal mountains on accreting neutron stars:
   sources of temperature non-axisymmetry*, MNRAS **522**, 226 (2023), [doi:10.1093/mnras/stad967](https://doi.org/10.1093/mnras/stad967).

## Installation and usage

Instructions will be added here once the first working version is in place.

## Citing

GitHub's **"Cite this repository"** button (in the sidebar) gives ready-made APA and BibTeX
entries based on [`CITATION.cff`](CITATION.cff).

## License

Released under the [BSD 3-Clause License](LICENSE).
