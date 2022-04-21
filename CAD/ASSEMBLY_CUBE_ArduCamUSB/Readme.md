# Camera Cube for the ArduCam USB
This is the repository for the Camera Cube.

To acquire the STL-files use go to the [STL-folder](./STL). The module can be built using injection-moulded (IM) or 3D-printed (3DP) cubes.

## Purpose
It adapts an ArduCam USB to the UC2 system.

<p align="center">
<img src="./IMAGES/Assembly_ArducamUSB.PNG" width="300">
</p>

The sensor is put into an adapter which holds the camera in the center of the cube. 

### Properties
* design is derived from the base-cube

## Parts
The [Bill of Materials](https://docs.google.com/spreadsheets/d/1U1MndGKRCs0LKE5W8VGreCv9DJbQVQv7O6kgLlB6ZmE/edit?usp=sharing) is always the most up-to-date version!

### <img src="../IMAGES/P.png" height="40"> 3D printing parts
* No support needed in all designs
* Carefully remove all support structures (if applicable)

The Cube consists of the following components.

#### Default:
* **IM Cube** which houses the insert and adapts it into a UC2 setup.
* **The Camera Insert** which holds the camera and makes it adaptable to the base-cube ([20_Cube_insert_Basler_acA1920_25gm_v3.stl](../RAW/STL))

#### Alternatives:
* **3DP Cube** which will be screwed to the Lid. Here all the functions (i.e. Mirrors, LED's etc.) find their place ([10_Cube_1x1_v3.stl](../RAW/STL)) and **3DP Lid** which closes the Cube ([10_Lid_1x1_v3.stl](../RAW/STL)) - find the details in [ASSEMBLY_CUBE_Base](../ASSEMBLY_CUBE_Base)


### <img src="./IMAGES/B.png" height="40"> Additional parts
* Check out the [RESOURCES](../../TUTORIALS/RESOURCES) for more information!
* 4× DIN912 M3×12 screws (galvanized steel) [🢂](https://eshop.wuerth.de/Zylinderschraube-mit-Innensechskant-SHR-ZYL-ISO4762-88-IS25-A2K-M3X12/00843%20%2012.sku/de/DE/EUR/)
* ArduCam USB (e.g. [AMAZON](https://www.amazon.com/Arducam-Camera-Raspberry-Windows-Android/dp/B07YHK63DS)


## <img src="./IMAGES/A.png" height="40"> Assembly
* Remove the outer PCB that encapsulates the camera
* Mount the camera to the insert using 4x M3 screws
* Take the mounted camera adapter inlet and slide it into the base-cube
* Close the cube accordingly (IM/3DP)
* Done!
