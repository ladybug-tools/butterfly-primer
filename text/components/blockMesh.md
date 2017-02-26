## ![](../../images/icons/blockMesh.png) blockMesh

![](../../images/components/blockMesh.png)

blockMesh -

#### Inputs
* ##### case [Required]
Butterfly case.
* ##### cellSizeXYZ [Default]
Cell size in (x, y, z) as a tuple (default: length / 5). This value updates number of divisions in blockMeshDict.
* ##### gradXYZ [Default]
A simpleGrading (default: simpleGrading(1, 1, 1)). This value updates grading in blockMeshDict.
* ##### overwrite [Default]
Remove current snappyHexMesh folders from the case if any (default: True). 
* ##### run [Required]
run blockMesh.

#### Outputs
* ##### readMe!
Reports, errors, warnings, etc.
* ##### case
Butterfly case.


[Check Hydra Example Files for blockMesh](https://hydrashare.github.io/hydra/index.html?keywords=Butterfly_blockMesh)