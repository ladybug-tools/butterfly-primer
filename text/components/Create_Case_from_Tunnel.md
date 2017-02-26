## ![](../../images/icons/Create_Case_from_Tunnel.png) Create Case from Tunnel

![](../../images/components/Create_Case_from_Tunnel.png)

Create Case from wind tunnel.

#### Inputs
* ##### name [Required]
Project name.
* ##### BFGeometries [Required]
List of butterfly geometries that will be inside the tunnel.
* ##### refRegions [Optional]
Script variable createCaseFromTunnel
* ##### windVector [Required]
A vector that indicates speed and direction of wind. Length
* ##### refWindHeight [Default]
Reference height for wind velocity (default: 10m).
* ##### landscape [Default]
An integer between 0-7 to calculate z0 (roughness).
* ##### make2dParams [Optional]
Butterfly parameters to make a 2d wind tunnel.
* ##### meshParams [Default]
Butterfly meshing parameters. You can set-up meshing parameters
* ##### tunnelParams [Default]
Butterfly tunnel parameters.
* ##### run [Required]
Create wind tunnel case from inputs.

#### Outputs
* ##### readMe!
Reports, errors, warnings, etc.
* ##### pts
Wind tunnel corners for visualization.
* ##### case
Butterfly case.


[Check Hydra Example Files for Create Case from Tunnel](https://hydrashare.github.io/hydra/index.html?keywords=Butterfly_Create Case from Tunnel)