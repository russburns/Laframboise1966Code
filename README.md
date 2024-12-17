# Laframboise1966Code

The Fortran II Programs used to make the numerical calculations as follows:


* Main Program 1: used to carry out computations for the general case.
* Main Program 2: used to carry out computations for the case of zero temperature repelled particles.
* Main Program 3: used together with subprogram COEFT to calculate the planar-sheath limit of the case of zero-temperature repelled particles as described in Appendix F.
* Main Program 4: used together with subprograms POWERS and CHASPH to obtain a numerical solution of the Allen, Boyd, and Reynolds equation (Ref. 6) as described in Appendix G.

* Subprograms ADJUST, COOKIE, CHARGE, CUBIC, POLATE, CHAMON, CAL, COEFT: used by main programs 1 and 2; COEFT is also used by mainprogram 3.
* Subprograms FIRST, SECOND, THIRD, FOURTH, UNO, DUO, TRE, SDFN: used together with main programs 1 or 2 to carry out calculations for spherical geometry.
* Subprograms FIRST, SECOND, THIRD, FOURTH, DYO, CDO, TRY, CORE: . Used together with main programs 1 or 2 to carry out calculations for cylindrical geometry.
