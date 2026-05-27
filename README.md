# Farm-Bike
## Preamble
A simultaneous engineering project at EPFL under the *Durabilité* unit, which aims to create a modular power source for various farm machinery utilizing human work as the source of power. The development of this machine is the work of a whole semester. The project describes every step from design to machining and testing. 
<table>
  <tr>
    <td><img src="https://github.com/ME-314/Farm-Bike/blob/main/Resources/PresentationPhoto0.jpg" width="350"></td>
    <td><img src="https://github.com/ME-314/Farm-Bike/blob/main/Resources/PresentationPhoto2.jpg" width="350"></td>
  </tr>
</table>
The machine built has successfully fulfilled the requirements outlined in the subsequent paragraphs, multiple farming implements were also retrofitted to be compatible with it. Testing showed promising results and the modularity of the design proved indispensable.  

The CAD models for this project can be found in the *CadParts* folder and the manufacturing and assembly drawings in the *Drafts* folder. The *Design* section shows general design intent and is aimed at anyone wanting to recreated as similar design or better understand this one. Meanwhile the *Manufacturing* section describes the most interesting challenges faced during the fabrication of this prototype. The safe operation of machinery used requires training that this document doesn't provide. For this reason the *Manufacturing* section is not a guide and omits operations that are trivial to readers familiar with metalworking. This section is intended to provide ideas on the order of operations or fabrication techniques.  Necessary processes are specified per part to help the evaluate the feasibly in accordance with available resources   

The following README contains that may overlap with other documentation contained in the repository but is not intended as a replacement for those documents. 


<a href="https://github.com/ME-314/Farm-Bike">ME-314 Farm-Bike</a> © 2026 by <a href="https://github.com/FSzymans">Franciszek Szymanski</a> is licensed under <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a>

<img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/nc.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/sa.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;">


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

![Render of the machine](https://github.com/ME-314/Farm-Bike/blob/main/Resources/FrameAssyRender.png "Render of the machine")

The render above outlines the key components of the machine.
### [Frame](https://github.com/ME-314/Farm-Bike/blob/main/Drafts/FrameAssembly.pdf)
The frame is made out of Item modular aluminium extrusions, specifically the profile 8 series. This made the construction of the frame simple and required only of the shelf parts. The Item profile 8 can be substituted by any equivalent 40 mm * 40 mm T-slot aluminium extrusion. This size of extrusions constrained the design to use M8 fasteners throughout. The choice of aluminium extrusion was made to ensure availability of materials in any geographical region as well as ensure repairability, the ease of manufacture was of course a welcome bonus.
### Drivetrain
A transmission based on bicycle components is the optimal of the self solution to our problem. It offers robustness, ease of maintenance and worldwide availability at a low cost. The following components in the system required no modification from their retail configuration: 
- Cassette 
- Derailleur & Shifter
- Handlebars & Stem
- Crank set & Bottom Bracket
- Seat post & Saddle 

The machine is designed to be used as a modular power source for various farming implements, many of which are hand cranked and operate are around 60 rpm. Gear ratios of the bicycle drivetrain and the sizes of the pulleys were chose in a way that allows the operator adjust the rotational speed up and down without stopping the machine. 

The subsequent paragraph describe the design of each of the machine specific parts. The parts were designed to conform with bicycle industry standards such that commissioning and maintenance could be carried out by anyone familiar with common bicycles.

#### Gear Ratios Calculation
With the chosen cassette and chainrings and an assumed cadence of 70 rpm the output of the machine can vary between 47 and 137 rpm. If necessary the size of driven pulley mounted to the farming implement can be adjusted to suit. To simplify adapting other machinery and further development the ratio calculation spread sheet is available in the documentation.

![Ratio Table](https://github.com/ME-314/Farm-Bike/blob/main/Resources/GearCalculations.png "Ratio Table")

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
## [Manufacturing](https://github.com/ME-314/Farm-Bike/blob/main/Drafts/FarmBikeAssembly.pdf) 
This section outlines the manufacturing processes of each of the parts and provides photos of the components. It assumes the reader is comfortable with conventional machining processes and general fabrication and thus omits the details of most trivial operations. Some parts in the assembly are overlooked in this section as their manufacturing features no operations of interest.
### [Bottom Bracket Shell](https://github.com/ME-314/Farm-Bike/blob/main/Drafts/BottomBracketMount.pdf) 
- TIG Welding
- Turning 

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

### [Axle](https://github.com/ME-314/Farm-Bike/blob/main/Drafts/DriveAxle.pdf)
- Turning 
- Milling

The machining operations did not deviate from standard practice. Loctite 603 retaining compound was used to chemically bond the freehub body to the axle. Chemical bonding was chosen to remove the need for pressing in the axle thus eliminating the risk of fracture on the hardened freehub body. 
### [Pillow Block](https://github.com/ME-314/Farm-Bike/blob/main/Drafts/PillowBlock.pdf)
- Turning 
- Milling
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


###  Fly Wheel
- Turning 
- If available fibre laser cutting or water jet

In order to avoid procuring costly stock material the fly wheel is cut out of 5 mm S235 structural steel and the pieces are pinned together. The use of a fibre laser allows for significant time saving but all of the parts can be machined using conventional process. The parts were pressed together with an arbor press and a coat of anti-rust primer protects against corrosion.
<table>
  <tr>
    <td><img src="https://github.com/ME-314/Farm-Bike/blob/main/Resources/FlyWheel0.jpg" width="350"></td>
    <td><img src="https://github.com/ME-314/Farm-Bike/blob/main/Resources/FlyWheel1.jpg" width="350"></td>
  </tr>
</table>

### [Hub](https://github.com/ME-314/Farm-Bike/blob/main/Drafts/HubExploded.pdf) 
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
- Metal Cutting
- Sheet Metal Bending
- If available fibre laser cutting or water jet

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
Normalized industrial parts for this project can be commonly bought new from well established suppliers. The parts for the prototype were sourced from [Norelem](https://www.norelem.ch/), but equivalent parts can be source from: 
- [Misumi](https://fr.misumi-ec.com/)
- [RS Components](https://us.rs-online.com/)
- [McMaster-Carr](https://www.mcmaster.com/)
- [JLCMC](https://jlcmc.com/)
In this project the part numbers specified on assembly drawings and in the cad model correspond to Norelem part numbers.  
To reduce the ecological impact of the prototype, second hand or recovered components were utilized in areas that would not impact the longevity, safety or operation of the machine.
Item aluminium profiles and relevant hardware were recovered from decommissioned machinery. Equivalents can be sourced from the suppliers above or Item24 directly. Wherever possible material off-cuts or scrapped parts we used as stock material.   
Bicycle components for the prototype were second hand and sourced from *Point Vélo* located on the EPFL campus. 
## User Guide 

### Prototype Overview

After the design and manufacturing phases, the **Farm-Bike prototype** was fully assembled.

The image below shows the assembled Farm-Bike prototype in its final pre-testing configuration. It highlights the complete mechanical structure, including the aluminium frame, the bicycle transmission, the rear wheel 10-speed cassette, the pedals, and the operator interface.

<p align="center">
  <img src="Resources/Pretesting_prototype.JPG" alt="Assembled Farm-Bike prototype in pre-testing configuration" width="800">
</p>

<p align="center">
  <em>Assembled Farm-Bike prototype.</em>
</p>

This final assembly represents the functional outcome of the project and serves as the basis for future improvements, such as ergonomic optimisation, stronger machine coupling, and further field testing at the farm.

### Use Instructions 
Before operating the machine, ensure that it is placed on a stable and level surface. The frame should not rock or move under load, and all fasteners securing the aluminium profiles, pillow block, bottom bracket shell, seat post and handlebar assembly should be checked for tightness. The pulley, flywheel and cassette should be visually inspected to ensure that they are correctly seated and that no foreign object is interfering with the drivetrain.

The user should adjust the saddle height and handlebar position to obtain a comfortable pedalling position. As with a conventional bicycle, the saddle height should allow the leg to remain slightly bent at the bottom of the pedal stroke. The drivetrain can then be shifted using the standard bicycle shifter in order to select the desired transmission ratio. The rear derailleur can be shifted using the standard handlebar shifter, while the front chainring selection has to be carried out manually. The user should therefore stop pedalling, wait for the drivetrain to come to rest, and move the chain by hand only when the machine is fully stationary. This should be done by getting off the bike, adjusting the chain to the desired chainring setting and gently cranking the pedals by hand such that the chain jumps into its desired place. The user can afterwards get back onto the bike and pedal normally. Lower gears should be used when starting the machine or when driving a high-load implement, while higher gears can be used once the system is already rotating smoothly or when a higher output speed is required.

To start the machine, the user should begin pedalling progressively and avoid sudden impacts on the pedals. The flywheel will gradually store kinetic energy and smooth out the power delivery. Once the machine is rotating steadily, the selected gear ratio can be adjusted depending on the required output speed and the resistance of the coupled machine. Gear changes should preferably be carried out while pedalling with moderate force, in the same way as on a standard bicycle, in order to avoid excessive stress on the chain and derailleur.

Before coupling the Farm-Bike to an external machine, the user must ensure that the driven machine is compatible with the output speed, torque and rotation direction of the system. The coupling should be securely mounted and aligned with the pulley or output shaft to avoid vibrations, belt slipping or premature wear. During operation, hands, clothing and loose objects must be kept away from the chain, cassette, pulley, flywheel and any rotating element.

To stop the machine, the user should simply reduce pedalling effort progressively and allow the drivetrain and flywheel to slow down naturally. The user should not attempt to stop the flywheel, pulley or chain by hand. After use, the machine should be inspected for loose fasteners, abnormal noise, chain misalignment or signs of wear. If the machine has been used outdoors or stored in humid conditions, exposed steel parts should be dried and checked for corrosion.

### Maintenance Guide 
Time intervals for preventative maintenance are a guidelines, maintenance intervals should be adjusted in accordance with conditions of use and storage. 
- each use inspect fasteners and drivetrain
- 7-10h clean and lubricate chain
- 30-50h degrease and lubricate chain
- 100h inspect drivetrain for wear
- 150h disassemble and inspect hub and crank set

Parts deemed inoperable during inspection are to be replaced 

For a more detailed explanation on fitting adjusting and maintaining bicycle specific components please refer to General Operations Manual *(ref:DM-GN0001)* published by Shimano.

### Troubleshooting Guide  
Common issues and their most common causes. 
- Unusual noise &rarr; Loose fastener &rarr; Verify and tighten fasteners
- Chain skips under power &rarr; Worn drivetrain components &rarr; Replace chain, if issue persists replace cassette and chainrings 
- Chain jumps between gears &rarr; Shifting not adjusted &rarr; Adjust shift cable
- Chain fall of top or bottom of cassette &rarr; Derailleur limits out of adjustment &rarr; Adjust derailleur limits
- Excessive friction in drivetrain under no load &rarr; Debris stuck or tangled in drivetrain &rarr; Inspect drivetrain and remove debris

## Testing 

### Initial Testing

The first functional test was carried out directly at the Bassenges farm. The Farm-Bike prototype was brought to the farm and connected to two existing machines: the polenta grinder and the corn sheller. Pulleys were installed on both machines, after which the bike was coupled to the system and tested. The first test was successful, as the Farm-Bike was able to drive the machines through the belt transmission. The whole Bassenges team was present during the test.

However, once the system was operating, an important ergonomic issue was identified by Timothée, the farmer responsible for following the project at the Bassenges farm. In the initial configuration, the bike was not facing the machines. This meant that a single operator could not comfortably pedal the bike and load the machines at the same time. This feedback highlighted an important practical limitation of the first assembly.

After considering the problem, we realized that the modular aluminium profile frame made it possible to rearrange the bike without manufacturing new parts. Several components were repositioned so that the pulley attachment faced the opposite direction and was located at the front of the bike. This reassembly took approximately an hour and a half, but it allowed the Farm-Bike to be adapted directly to the farmer's request. Due to the lack of equipment at the farm, we were not able to reduce the length of the chain (due for next week).

Initial testing confirmed the value of using modular aluminium profiles for the frame. The ability to modify the geometry of the machine on site was a major advantage during the testing phase. If the frame had been fully welded or made as a fixed steel structure, this last-minute correction would not have been possible without significant rework.

The following images show the Farm-Bike before and after the reassembly:

<table>
  <tr>
    <td><img src="https://github.com/ME-314/Farm-Bike/blob/main/Resources/Test1_Before.jpg" width="450"></td>
    <td><img src="https://github.com/ME-314/Farm-Bike/blob/main/Resources/Test1_After.JPG" width="450"></td>
  </tr>
  <tr>
    <td align="center"><em>Initial configuration</em></td>
    <td align="center"><em>Modified configuration</em></td>
  </tr>
</table>

### Second Testing Session

The second day of testing allowed the team to further adapt the **Farm-Bike prototype** based on the observations made during the first trial.

In particular, the chain length was adjusted and the seating position was modified accordingly. The overall design proved to be functional; however, the shortening of the chain had an effect on the shifting performance. Gear changes became less smooth than before, and the most extreme gear-ratio settings became more difficult to use.

Another important feedback point was given by **Timothée**, who suggested keeping the inertial wheel attached to the corn sheller. In response to this, the pulley transmission was modified. Instead of removing the inertial wheel, the pulley system was attached to the rear side of the transmission axle, replacing an old unused gear. This allowed the inertial wheel to be reinstalled on the machine while still maintaining the connection between the Farm-Bike and the corn sheller.

The following day, the team returned to the farm to make additional ergonomic and functional improvements. The shifting cable was shortened, and the stem was lengthened in order to improve both the shifting accessibility and the seating position. These modifications made the system more comfortable to operate and better adapted to the user during testing.

The image below shows the Farm-Bike connected to the corn sheller during the testing phase.

<p align="center">
  <img src="Resources/FarmBike_CornSheller.JPG" alt="Farm-Bike prototype connected to the corn sheller during testing" width="800">
</p>

<p align="center">
  <em>Farm-Bike prototype connected to the corn sheller during testing.</em>
</p>

## Conclusion
