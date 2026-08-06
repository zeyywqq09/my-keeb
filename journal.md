Welcome to my diary!

## Day 1 (01.08.2026)
* **(11.00 AM - 12.00 PM):** Layout Design & Switch Plate Preview (1 Hour)
  * Designed a custom 65% ANSI layout using Keyboard Layout Editor.
  * Generated the switch plate layout (including switch cutouts and stabilizer mounting points) using SwillKB Builder.

* **Switch Plate:**
  <img width="1226" height="392" alt="image" src="https://github.com/user-attachments/assets/deae869e-43ae-43f4-9ef8-4f5904144a9f" />

* **Note:** A layout preview screenshot of the updated 65% switch plate generated via SwillKB Builder.

## Day 2 (06.08.2026) (2 hour 15 min)
Hi! It actually looked a bit intimidating today since it's my first keyboard, but—as the saying goes (I don't know who said it, though :D)the important thing is to get started!

* **(10.00AM-12.15PM)**:I started drawing the electronic circuit diagram of the keyboard.
* First of all, I employed a matrix (row and column) approach. Connecting every single button to the controller individually would require separate pins or cables for each one; however, with the matrix method, we can arrange the buttons in a grid-like pattern of rows and columns. This allowed me to cut the number of required pins in half.
* After that, I added the diodes. Diodes prevent electrical leakage, ensuring that pressing multiple keys simultaneously doesn't result in an unpressed key registering as pressed. This allows my keyboard to register every single key press flawlessly.
* <img width="708" height="319" alt="image" src="https://github.com/user-attachments/assets/d59afb88-04e6-499c-9a23-6f3db5b76b41" />

Update (12:44 PM): This is starting to get more tiring, guys :(

Hey, I'm back—the schematic drawing and electrical checks are all done!(15.35PM)
<img width="727" height="258" alt="image" src="https://github.com/user-attachments/assets/c2a7e244-c4e3-400b-ab3f-c8bc67177059" />

## Update (15.55PM)
I selected the Cherry MX-compatible switch footprints.
I assigned the SW_Cherry_MX_1.00u_PCB footprint to all mechanical switches.
I began preparing the physical switch layout for the PCB design.
* <img width="530" height="533" alt="image" src="https://github.com/user-attachments/assets/81cdfeaa-a85a-4a15-9f34-30829b273fbb" />
## (16.45PM)
Ohh, I just ran KiCad's ERC and a damn problem popped up, but no matter how long it took, I got it sorted out.

## Same day (18.00PM-21.00PM)

I finally moved on to the PCB part.
* Instead of soldering switches, I chose Kailh Hotswap socket support—which allows for easy replacement—and 5-pin MX-compatible footprints (SW_Hotswap_Kailh_MX_1.00u).
* I integrated the custom keyboard library (PCM_marbastlib-mx), which contains mechanical keyboard components and footprints, into KiCad.
* I have placed 6 M2 screw holes (H1–H6) on the schematic for mounting to the case.
* To balance the large keys, I added a total of five stabilizer symbols—one 6.25u (Spacebar) and four 2u (Shift, Enter, Backspace)—and assigned reference numbers to them.
* I assigned SMD footprints to the diodes and 2.2mm M2 mounting holes to the screw holes.
* I assigned the appropriate plate-mount footprints from the library to the stabilizer symbols in the schematic.
  <img width="544" height="397" alt="image" src="https://github.com/user-attachments/assets/2eef4764-21bf-4b48-822a-ed957ae7b1f2" />

