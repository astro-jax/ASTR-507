This is the repository for the ASTR 507 (Stellar Archaeology) Spring 2024 graduate course.

Some of these are interesting code from students who have taken the course,
and others are the jupyter notebooks made for illustrating various assignments.

Cosmological Simulations
	Assignment 1: Use the mock dataset from AuriGaia to create some interesting plots !
		(AuriGaia is a mock catalogue replicating observations in Gaia. The data are from a handful of
		simulated haloes resembling the MW.)

Globular Clusters:
	Assignment 3: Select a MW globular cluster, and obtain a 2 deg field of stars for this system in Gaia.
		Clean the data and remove as much MW contamination as possible. Make some interesting plots, in
		particular:
			* Equatorial and tangent plane coordinates 
			* 3-D or Aitoff projection
			* Stellar density profile

Deriving Distances & Stellar Parameters (Federico Guest Section):
	Assignment 4: Students will either a) download the sample of UMPs from Sestito+2019. Derive distances and
		stellar parameters, or b) select a dwarf galaxy and download a field of stars in/around this system
		from Gaia. Clean the sample and derive stellar parameters for candidate members. 
	(assignment requires proper dustmaps download; jupyter notebook for this assignment indicates how to properly 
	install this package and download necessary dust maps)

M31 (Alan Guest Section):
	Assignment 5: Use the mock dataset from AuriPAndAS to create some interesting plots !
		(AuriPAndAS is a mock catalogue replicating observations in PAndAS. The data are from a handful of 
		simulated haloes resembling the MW-M31 pair.)
		Students will select one (or a few) general topics. Some recommendations:
			* Make a stellar density profile of M31 using only the stars assumed to be in-situ. You can 
				then compare this to the "smooth" accretion of M31 (as seen in the profiles from 
				PAndAS publications & Thomas+21 i.e. Figure 9) or the stellar density profile of the MW.
			* Justify various substructures and "groups" of stars; then confirm with the simulation as 
				to whether these are indeed accreted substructures. Map these using the RGB matched 
				filter method.
			* Compare/contrast all haloes \& their stellar distributions in a meaningful (possibly quantitative) way.
			* Fraction of accreted stars as a function of radius.
			* etc.

Dark Matter (Julio Guest Section):
	Assignment 6: Run an N-body simulation of UMa3/U1 (Simon+24) in GADGET. The simulation setup is from Errani+2023 (citations
		listed in jupyter notebook).
		Suggested tasks to complete:
			* Plot the orbit of UMa3/U1 projected to (x, y, z) and in Galactocentric distance (R) as a function of time.
			* Plot the evolution of the mass contained wihtin a sphere of radius 10 pc around the center of density. How
				long does it take until the system fully disrupts ?
			* Change the initial mass M of the system so that it survives for 4, 8, and 12 Gyrs. Plot the mass evolution
				for each case. HINT: Use Fig 1 from Errani+24 as guidance.
			* Imagine UMa3/U1 was on a circular orbit. Find suitable initial conditions for such a circular orbit, 
				consistent with the current-day position (x, y, z) of UMa3/U1. HINT: see circular velocity curve of
				the adopted Galaxy model. Repeat the analysis above for this new orbit. 
		
