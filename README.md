# CD-simulations
Applets for the simulation of CD spectra and properties

**Gaussian sum and difference simulator**

Interactive simulation of the sum and difference of two Gaussian bands with independently adjustable center wavelengths (λ₁, λ₂), common bandwidth (σ), and intensities (ε₁, ε₂). Vertical markers indicate the maxima and minima of the individual components and of the resulting curve. A toggle forces equal intensities for the two components in the difference plot, useful for illustrating the dependence of band position and shape on the degree of overlap.

**Kramers–Kronig CD/ORD simulator**

Interactive simulation of the Kramers–Kronig relation between circular dichroism (CD) and optical rotatory dispersion (ORD) spectra. Illustrates how unobservable CD bands below 185 nm contribute a baseline offset to the visible ORD curve, and why the KK transform is quantitatively inapplicable over a truncated spectral range. Built with Chart.js; no dependencies beyond a modern browser.

**Exciton coupling simulator: 1,2-bis(benzoate)**

Interactive simulation of the exciton-coupled absorption and CD spectra of a 1,2-diol bis-benzoate, based on real molecular coordinates. The O–C–C–O dihedral angle controls the relative position and orientation of the two benzoate transition dipoles, from which the coupling energy V and rotatory strength R are computed explicitly via the point-dipole approximation. In the V ≪ σ regime (always satisfied here), the CD spectrum is shown as proportional to R·V·(dε/dλ), the characteristic bisignate derivative shape of exciton-coupled chromophores.
