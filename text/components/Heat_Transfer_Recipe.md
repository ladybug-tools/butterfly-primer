## ![](../../images/icons/Heat_Transfer_Recipe.png) Heat Transfer Recipe

![](../../images/components/Heat_Transfer_Recipe.png)

Heat Transfer Recipe. -

#### Inputs
* ##### turbulenceProp [Default]
Turbulence properties. This values will overwrite default values, and can be updated while the solution is running.
* ##### temperature [Default]
Reference temperature in degrees celsius. Default is set to 26.85 C (300 K) degrees.
* ##### fvSchemes [Optional]
Optional input for fvSchemes to overwrite default fvSchemes.
* ##### fvSolution [Optional]
Optional input for fvSolution to overwrite default fvSolution.
* ##### residualControl [Optional]
residualControl values. This values will overwrite default values, and can be updated while the solution is running.
* ##### relaxationFactors [Default]
relaxationFactors. This values will overwrite default values, and can be updated while the solution is running.

#### Outputs
* ##### readMe!
Reports, errors, warnings, etc.
* ##### recipe
Script variable Python


[Check Hydra Example Files for Heat Transfer Recipe](https://hydrashare.github.io/hydra/index.html?keywords=Butterfly_Heat Transfer Recipe)