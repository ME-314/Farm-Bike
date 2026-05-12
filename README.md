# Farm-Bike
## Preamble
A simultaneous engineering project at EPFL under the *Durabilité* unit, which aims to create a modular power source for various farm machinery utilizing human work as the source of power. The development of this machine was the subject of a simultaneous engineering project (course code: ME-314) and is the work of a whole semester. The project describes every step from design to machining and testing. 
![Render of the machine](https://github.com/ME-314/Farm-Bike/blob/main/Resources/FrameAssyRender.jpg "Render of the machine")
**ADD CONCLUSION ON FINAL RESULT** 
The following README contains that may overlap with other documentation contained in the repository but is not a replacement for those documents.  
## Specification 
#### Functionality 
- Provide a way of converting human power into useful shaft work
- Have easily adjustable transmission ratio
- Allow for quick coupling of multiple machines
#### Work Environment 
- Resist an outdoor work environment subject to a central European climate
- Resist storage in wet conditions
#### Durability
- Be built where ever possible out of standard parts to ensure long term parts availability
- Machined component to only use conventional machining to provide possibility of field repair
- Use of quality components to ensure a long life cycle  
- Easy maintenance procedures
## Design 
The design of the machine was driven by the specification outlined above and the will to ensure the project can be replicated or further developed in the future. The design choices are driven by the will to create a machine that has a long service life, quality parts and material were chosen over low-cost alternatives.
### Frame
The frame is made out of Item modular aluminium extrusions, specifically the profile 8 series. This made the construction of the frame simple and required only of the shelf parts. The Item profile 8 can be substituted by any equivalent 40 mm * 40 mm T-slot aluminium extrusion. The choice of aluminium extrusion was made to ensure availability of materials in any geographical region as well as ensure repairability, the ease of manufacture was of course a welcome bonus.
### Drivetrain
A transmission based on bicycle components is the optimal of the self solution to our problem. It offers robustness, ease of maintenance and worldwide availability at a low cost. The following components in the system required no modification from their retail configuration: 
- Cassette 
- Derailleur & Shifter
- Handlebars & Stem
- Crank set & Bottom Bracket
- Seat post & Saddle 

The subsequent paragraph describe the design of each of the machine specific parts. The parts were designed to conform with bicycle industry standards such that commissioning and maintenance could be carried out by anyone familiar with common bicycles.
#### Bottom Bracket Shell
The bottom bracket shell attaches the standard BSA bicycle bottom bracket to the frame. The part is a weldment of a round bottom bracket shell recovered from a donor frame and a 40 mm * 30 mm rectangular steel tube. The part requires far less material resources then an equivalent machined from a billet and does not require specialty tooling to cut the BSA thread. 
#### Hub
The hub forms a central part of the transmission of the machine, it the mounts the cassette and the pulley thus transmitted all of the power generated. A flywheel is also mounted on the axle to smooth out the power delivery.  
##### Pillow Block
This part houses the main bearings and attaches to the frame. It is a crucial parts that maintains the alignment between that two bearing and ensures their long life and smooth operation, for this reason it is machined out of a 6061 Aluminium billet. Due to unavailability of appropriate stock the pillow block has been split into two pieces and pinned together. It features clearance holes for two M8 mounting bolts, a central bore for the axle to pass through and two counterbores for the 6005-2Z bearings. These deep groove ball bearings have been selected to ensure a long life span as well being easy to source. Low profile ball bearing often found in bicycles have specifically been discarded as their lower profile makes them more prone to premature failure. A recess has been added at the mounting between the pillow block and the aluminium profile to prevent twisting during usage.  
##### Axle
The large bearings allow us to use an aluminium axle without risking the keyway becoming fragile. The axle features 25 mm bearing seats and a key way to transmit torque to the flywheel and pulley. In order to mount the cassette onto the axle while avoiding complex machining operations a donor freehub body was bonded onto the axle. The axle was of course designed around the specific freehub body available thus the design would need to be modified in accordance with available parts. 
#### Derailleur Hanger
To emulate the derailleur mounting of a conventional bicycle without having to cut a fine pitch thread a derailleur hanger from a donor frame was utilized. In order to correctly position it with respect to the axle and cassette a mount was designed out of 3mm 5005 aluminium sheet. The mount exploits the advantages of bent sheet metal to achieve a robust yet lightweight solution. 
## Manufacturing 
This section outlines the manufacturing processes of each of the parts and provides photos of the components. It assumes the read is comfortable with conventional machining processes and general fabrication and thus omits the details of most trivial operations. Some parts in the assembly are overlooked in this section as their manufacturing features no operations of interest. 
### Bottom Bracket Shell 
This is the only weldment on the machine, consisting of two parts with thin sections. The donor frame was chose for its steel construction and BSA threaded bottom bracket. The shell was cut out and turned down to a constant diameter. During the turning operations a close fitting aluminium plug was used on the inside of the threads to provide tailstock support. The hole for the shell in the rectangular tubing was roughed out with a hole saw on a mill and fitted by hand with a file. The two parts were subsequently TIG welded and the thread was chased. TIG welding was used because of the thin material and in order to preserve as much of the BSA thread inside the shell.     
<table>
  <tr>
    <td><img src="https://github.com/ME-314/Farm-Bike/blob/main/Resources/BottomBracketShell0.jpg" width="350"></td>
    <td><img src="https://github.com/ME-314/Farm-Bike/blob/main/Resources/BottomBracketShell1.jpg" width="350"></td>
  </tr>
  <tr>
    <td><img src="https://github.com/ME-314/Farm-Bike/blob/main/Resources/BottomBracketShell2.jpg" width="350"></td>
    <td><img src="https://github.com/ME-314/Farm-Bike/blob/main/Resources/BottomBracketShell3.jpg" width="350"></td>
  </tr>
</table>
After welding, the oxides were removed and the part was finished with automotive anti-rust primer. 

### Axle
The machining operations did not deviate from standard practice. Loctite 603 retaining compound was used to chemically bond the freehub body to the axle. Chemical bonding was chosen to remove the need for pressing in the axle thus eliminating the risk of fracture on the hardened freehub body. 
### Pillow Block
Due to limitations in the available stock material the pillow block was machined from two separate pieces of stock. 
[![Watch the video](https://github.com/ME-314/Farm-Bike/blob/main/Resources/PillowBlockBoring.mp4)](https://github.com/ME-314/Farm-Bike/blob/main/Resources/PillowBlockBoring.mp4)

The operations were carried out in the following order: 
- Squaring the stock to size 
- Drilling and reaming of the 4mm pin bores
- Centre drilling of the main bore
- Two parts are pressed together 
- Milling locating slot 
- Drilling of two M8 clearance holes
- Boring half of the through bore in a lathe with centre drill hole as reference
- Boring of bearing seat
- Part flipped an boring operations repeated
- Deburring and chamfering 

<table>
  <tr>
    <td><img src="https://github.com/ME-314/Farm-Bike/blob/main/Resources/PillowBlock0.jpg" width="350"></td>
    <td><img src="https://github.com/ME-314/Farm-Bike/blob/main/Resources/PillowBlock1.jpg" width="350"></td>
  </tr>
  <tr>
    <td><img src="https://github.com/ME-314/Farm-Bike/blob/main/Resources/PillowBlock2.jpg" width="350"></td>
    <td><img src="https://github.com/ME-314/Farm-Bike/blob/main/Resources/PillowBlock3.jpg" width="350"></td>
  </tr>
</table>
Following machining, deburring and finishing was carried out and the bearings were fitted


### Fly Wheel
In order to avoid procuring costly stock material the fly wheel is cut out of 5 mm S235 structural steel and the pieces are pinned together. The use of a fibre laser allows for significant time saving but all of the parts can be machined using conventional process. The parts were pressed together with an arbor press and a coat of anti-rust primer protects against corrosion.
<table>
  <tr>
    <td><img src="https://github.com/ME-314/Farm-Bike/blob/main/Resources/FlyWheel0.jpg" width="350"></td>
    <td><img src="https://github.com/ME-314/Farm-Bike/blob/main/Resources/FlyWheel1.jpg" width="350"></td>
  </tr>
</table>

### Hub 
Precaution taken during assembly of the hub:
- Parts cleaned and lubricated 
- Light preload applied to the bearings 
- Taper lock pulley and bushing torqued to manufacturer specification

<table>
  <tr>
    <td><img src="https://github.com/ME-314/Farm-Bike/blob/main/Resources/HubAssy1.jpg" width="350"></td>
    <td><img src="https://github.com/ME-314/Farm-Bike/blob/main/Resources/HubAssy2.jpg" width="350"></td>
  </tr>
</table> 

### Derailleur Mount
Just like the fly wheel the derailleur mount was cut with the use of a fibre laser. Due to its non trivial geometry the sheet metal part was bent in a bench vice with the help of parallel jaw pliers. The existing derailleur hanger was hand fitted during the finishing process. As most of the parts geometries are non mating surfaces the part could be replicated with hand tools. The geometry cam be modified to suit the manufacturing methods available.
<table>
  <tr>
    <td><img src="https://github.com/ME-314/Farm-Bike/blob/main/Resources/DerailleurMount0.jpg" width="350"></td>
    <td><img src="https://github.com/ME-314/Farm-Bike/blob/main/Resources/DerailleurMount1.jpg" width="350"></td>
  </tr>
  <tr>
    <td><img src="https://github.com/ME-314/Farm-Bike/blob/main/Resources/DerailleurMount2.jpg" width="350"></td>
    <td><img src="https://github.com/ME-314/Farm-Bike/blob/main/Resources/DerailleurMount4.jpg" width="350"></td>
  </tr>
</table> 

## Procurement Guide 
Normalized industrial parts for this project can be commonly bought new from well established suppliers. The parts for the prototype were sourced from Norelem, but equivalent parts can be source from: 
- Misumi
- RS Components
- McMaster-Carr
- JLCMC

To reduce the ecological impact of the prototype second hand or recovered components were utilized in areas that would not impact the longevity, safety or operation of the machine.
Item aluminium profiles and relevant hardware were recovered from decommissioned machinery. Equivalents can be sourced from the suppliers above or Item24 directly. Wherever possible material off-cuts or scrapped parts we used as stock material.   
Bicycle components for the prototype were second hand and sourced from *Point Vélo* located on the EPFL campus. 
## User Guide 

### Use Instructions 

### Maintenance Guide 

### Troubleshooting Guide  

## Testing 

