WDIFMR v1.0
===========

This release contains the current recommended empirical white dwarf 
initial-final mass relation (IFMR) sample from wdifmr.org.

The table combines the sample presented in Miller et al. (2026a) 
with subsequent additions from Miller et al. (2026b). 
Future releases will expand this catalogue while preserving 
all previous versions for reproducibility.

-------------------------
STANDARDIZED OBJECT NAMES
-------------------------

The wd_name column contains the standardized wdifmr object identifier
adopted by wdifmr.org. Object names follow the convention

    Cluster-WD-JHHMMSS±DDMMSS

where the coordinate-based identifier is constructed from the adopted
J2000 right ascension and declination.

Cluster names are taken from the primary names adopted by Hunt &
Reffert (2023; 2023A&A...673A.114H), except for particularly well-known
clusters where common names are retained (e.g. Hyades, Pleiades,
and Praesepe).

The columns miller2026a_name and miller2026a_literature_name provide
cross-identifications with the naming conventions used in Miller et al.
(2026a).

-------------------
COLUMN DESCRIPTIONS
-------------------

name                         Standardized WDIFMR object identifier.
cluster                      Host cluster name.
ra                           Right ascension (ICRS, decimal degrees).
dec                          Declination (ICRS, decimal degrees).
coord_source                 Source of the adopted coordinates.
gaiadr3                      Gaia DR3 source identifier.
gaia_supported               Whether Gaia astrometry supports cluster membership (y/n).
logg                         White dwarf surface gravity, log(g/cm s^-2).
logg_err_plus                Upper uncertainty on logg.
logg_err_minus               Lower uncertainty on logg.
teff                         Effective temperature (K).
teff_err_plus                Upper uncertainty on teff (K).
teff_err_minus               Lower uncertainty on teff (K).
spectrum_fit_source          Source of the adopted atmospheric-parameter fit.
mass                         White dwarf mass (Msun).
mass_err_plus                Upper uncertainty on mass (Msun).
mass_err_minus               Lower uncertainty on mass (Msun).
tcool                        White dwarf cooling age (Myr).
tcool_err_plus               Upper uncertainty on tcool (Myr).
tcool_err_minus              Lower uncertainty on tcool (Myr).
rad                          White dwarf radius (km).
rad_err_plus                 Upper uncertainty on rad (km).
rad_err_minus                Lower uncertainty on rad (km).
prog_mass                    Initial (progenitor) mass (Msun).
prog_mass_err_plus           Upper uncertainty on prog_mass (Msun).
prog_mass_err_minus          Lower uncertainty on prog_mass (Msun).
ifmr_source                  Publication providing the adopted IFMR quantities.
simbad_name                  SIMBAD identifier, when available.
miller2026a_name             Object identifier used in Miller et al. (2026a).
miller2026a_literature_name  Literature identifier compiled in Miller et al. (2026a).

----------
REFERENCES
----------

Miller, D. R., et al. 2026a, ApJ, 996, 69
The White Dwarf Initial-Final Mass Relation from Open Clusters in Gaia DR3

Miller, D. R., et al. 2026b, ApJ, accepted
Investigating the Observational Progenitor Mass Gap in the White Dwarf
Initial-Final Mass Relation. I. Cluster Census and Characterization of
the First White Dwarfs in the Gap.

--------
CITATION
--------

If you use these data, please acknowledge https://wdifmr.org and cite the
relevant publications associated with the adopted data.

---------
CHANGELOG
---------

v1.0 - July 22, 2026
Initial release. Includes the Miller et al. (2026a) sample and 
the Miller et al. (2026b) mass-gap additions.

-------
CONTACT
-------

David R. Miller
Department of Physics and Astronomy
The University of British Columbia

drmiller@phas.ubc.ca