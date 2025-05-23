# Laframboise1966Code

As part of my senior Honors thesis, I am developed a model to predict Langmuir probe IV curves for given input parameters. To provide an accurate description of the notroiously tricky electron saturation region, I am referencing James G. Laframboise's 1966 well-cited thesis, "THEORY OF SPHERICAL AND CYLINDRICAL LANGMUIR PROBES IN A COLLISIONLESS, MAXWELLIAN PLASMA AT REST". I am also using the thesis to better understand the role of high-potential sheath expansion (in the planar limit of a small debye length). Laframboise's Fortran II Programs "MAIN PROGRAM 2" and "MAIN PROGRAM 3" respectively address those questions. Laframboise provides analysis of many different plasma parameter values, though I assume the following: 
* Electron temperature distribution (T-) is maxwellian
* Ion temperature (T+) is approximately 0K
* The probe is cylindrical

I used a guide to decode MAIN PROGRAM 3's Fortran II code, and I translated its logic into Python. Much of his computation is spent simply setting up the facilities and approximations necessary to perform integration--the numerical results were nearly identical to my modern program.
MAIN PROGRAM 2 is a much more detailed program, so whittling it down will be an arduous process. It uses gridded computation nets, which are straightforward enough in Python but likely nebulous in Fortran II.

In addition, I used Chen's parameterization of the "MAIN PROGRAM 1" output to provide a formula for ion current.

All relevant Fortran II code for each program wzas hand-transcribed and is included as part of each .ipynb.
  
The final thesis can be found here: https://scholarworks.wm.edu/honorstheses/2416/
