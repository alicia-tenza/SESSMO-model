README — SESSMO Model: Policy options under climate change
Version 1.0 (March 16, 2026)

Tenza-Peral, A., Pérez-Ibarra, I., Martínez-Fernández, J., Breceda, A. & Giménez, A.

Associated publication: Tenza-Peral et al. (2026). When the best becomes the enemy of the good: Rethinking resilience strategies under uncertainty.

--------------------------------------------------------------------------------

REQUIREMENTS

To run this model you need Vensim Model Reader (version 10.x or higher), which is free software available at: https://vensim.com/free-download/

--------------------------------------------------------------------------------

FILES INCLUDED

- SESSMO_Policy options under climate change.vpmx — Main model file (open this first)
- EXTERNAL_DATA.vdfx — External variables data (must always be loaded)
- TREND_CLIMATE.vdfx — Trend precipitation scenario
- FAVORABLE_CLIMATE_n.vdfx — Favorable climate scenario (15 series)
- UNFAVORABLE_CLIMATE_n.vdfx — Unfavorable climate scenario (15 series)

--------------------------------------------------------------------------------

HOW DOES IT WORK?

STEP 1. To play with the SESSMO model and see what happens to the oasis under different policy options and climate scenarios, open the window called "Exploring scenarios".

STEP 2. In the "Exploring scenarios" window you will find different levers to activate and deactivate the different policy options described in the "Management measures and policy options" window. There are also display boxes that will show the simulation results for the most relevant variables of the system (e.g. the dynamics of the human population, livestock, agriculture, employment or the local economy).

STEP 3. Give your simulation a name in "Run Name".

STEP 4. Load the external data needed to run your simulations. To do this, click on the "Simulation control" button, then on "Data". By clicking the "+" button, add the external data you need. The SESSMO model requires some external data to function (such as product price data, labour costs, and precipitation data). Therefore, for every simulation we run, we must ensure that the file "EXTERNAL_DATA.vdfx" is always loaded. In addition to that file, precipitation data must always be loaded, so for each simulation you need to choose which precipitation scenario you want to use: TREND (with the file "TREND_CLIMATE.vdfx"); FAVORABLE (with the file "FAVORABLE_CLIMATE_n.vdfx"); UNFAVORABLE (with the file "UNFAVORABLE_CLIMATE_n.vdfx"). There are 15 different precipitation series for the favorable climate scenario, and 15 for the unfavorable scenario.

STEP 5. Click on the "SyntheSim" button within "Simulation control", or on the "Run simulation on each slider change" button in the main toolbar. Once done, you will be able to activate (by moving the lever to "1") and deactivate (by moving the lever to "0") each of the policy options. By default, all policy options are deactivated (levers at value "0"). More than one policy option can be activated at a time, thus allowing the combined effect of the policy options to be observed. The simulation results for the key variables of the model will be displayed immediately as graphical outputs.

--------------------------------------------------------------------------------

GENERAL RECOMMENDATIONS TO AVOID ERRORS OR FAILURES IN SIMULATIONS

1. Make sure to always load the "EXTERNAL_DATA.vdfx" file + the climate scenario you want to simulate.

2. Before running any simulation, give it a name. If you forget, the new simulation results will overwrite the previous simulation.

3. Try to give each simulation a name that helps you quickly identify what you are simulating (e.g. RESISTANCE_CC_FAVORABLE; RESISTANCE+ADAPTATION_CC_UNFAVORABLE).

4. You can combine all the policy options you want at the same time, except for trying to activate both local transformation and transformation by external agents simultaneously. Under the current structure of the SESSMO model, these policy options are not compatible: either one occurs or the other.

5. Every simulation you run will be automatically saved with the filename "Simulation name.vdfx". By opening the Control Panel you can see which simulation files are available on your computer ("Available datasets") and which ones are loaded in Model Reader for visualization ("Loaded datasets"). This way you can load and unload whichever files you want for visualization in the simulation tool.

--------------------------------------------------------------------------------

CONTACT

For questions about the model, please contact: [atenza@unizar.es; alicia.tenza@gmail.com]
