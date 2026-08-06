# my-keeb ⌨️

## What am I doing?
I am designing and building my own custom 65% ANSI mechanical keyboard. I started by creating the key layout and designing a switch plate for laser cutting.

## Why am I doing it?
I chose this project because I am interested in engineering, electronics, and product design. A mechanical keyboard combines all of these areas in one project.

I want to understand how a device that I use every day is designed and built. Instead of only assembling ready-made parts, I want to design important parts of the keyboard myself.

## What do I want to learn?
I want to learn the full process of building a keyboard, including layout design, CAD modelling, PCB design, electronic components, soldering, firmware development, testing, and documentation.

I also want to improve my problem-solving skills by identifying design mistakes, testing different solutions, and documenting how I solved each problem.

## Day 1 (01.08.2026)
* **(11.00 AM - 12.00 PM):** Layout Design & Switch Plate Preview (1 Hour)
  * Designed a custom 65% ANSI layout using Keyboard Layout Editor.
  * Generated the switch plate layout (including switch cutouts and stabilizer mounting points) using SwillKB Builder.

* **Switch Plate:**
  <img width="1226" height="392" alt="image" src="https://github.com/user-attachments/assets/deae869e-43ae-43f4-9ef8-4f5904144a9f" />

* **Note:** A layout preview screenshot of the updated 65% switch plate generated via SwillKB Builder.

## Tools Used
- Keyboard Layout Editor
- SwillKB Builder
- GitHub

## Day 2 (06.08.2026) (2 hour 15 min)
* **(10.00AM-12.15AM)**:I started drawing the electronic circuit diagram of the keyboard.
* First of all, I employed a matrix (row and column) approach. Connecting every single button to the controller individually would require separate pins or cables for each one; however, with the matrix method, we can arrange the buttons in a grid-like pattern of rows and columns. This allowed me to cut the number of required pins in half.
* After that, I added the diodes. Diodes prevent electrical leakage, ensuring that pressing multiple keys simultaneously doesn't result in an unpressed key registering as pressed. This allows my keyboard to register every single key press flawlessly.
* <img width="708" height="319" alt="image" src="https://github.com/user-attachments/assets/d59afb88-04e6-499c-9a23-6f3db5b76b41" />

## Tools Used
- Github
- KiCad
