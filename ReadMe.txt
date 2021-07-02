July 1st, 2021

﻿Triple layer electrical signal propagation along actin filaments code (version 1.0)

This code was used to generate the results included in the article "Electrical Propagation of Condensed and Diffuse Ions Along Actin Filaments" published in the Journal fo Computational Neuroscience. 

You must have the commercial Mathematica software version 12.0 or higher to run this code.

The main directory “computational code” contains the folder resultsNotebooks and the notebook initialiationNotebook.nb

First step
The user must open (double click) and run (go to evaluation in the tool bar and click evaluate notebook) the initialiationNotebook.nb. This notebook defines all the expressions of the theory. It only needs to be run once and must be run first.  

Second step
The user must open the folder resultsNotebooks.

Third step
There are 7 notebooks in the resultsNotebooks folder. The user must select one, open (double click) and run (go to evaluation in the tool bar and click evaluate notebook) the notebook with the desired conditions to be analyzed. 

For instance, the notebook  “V0p05V_Ca1mM.np” will generate the results for the input voltage 0.05V and Calcium concentration 1mM, and so on. 

Note: All the results will be generated for a relative condensed dielectric permittivity value of  5 and relative diffuse permittivity of 78.54.  

Each results notebook will generate the following outputs:

The plots for the velocity as a function of the time v(t), the linearized mean electric potential  as a function of the radial distance Phi(r); the amplitude depending on the time Omega(t); and the soliton profiles V(x,t) for specific time snapshots (see the article more information).

It will also generate the following parameters: the condensation thickness; the axial and transversal currents; the diffuse and condensed resistances and equivalent resistances;  the diffuse and condensed capacitances and equivalent capacitances; and the impedance. It will also generate the soliton parameters. 

Note: you can only run one results notebook at the time. You cannot run two or more results notebooks ***TYPO simultaneously***. 

You can change any parameter in the result notebooks as needed. 

The computing time depends on the user computer performance. All the calculations are performed in a single processor. 

You are allowed to make any change on this code at your own risk. 

The open source version of this code will be integrated into the JACFC web application in the webiste http://neuronanobiophysics.utsa.edu/.

For additional information or questions please contact Dr. Marcelo Marucho
Email: csdfts.comphys@gmail.com
