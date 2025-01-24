> **EXP07--Design-Implementation-of-Comparator-using-Cadence-EDA-Tools*****

Procedure for Schematic simulation using Cadence

Now two windows must open i)virtuoso/command interpreter window ii)”Whats New…”
Close the 2nd window
Use 1st window i.e virtuoso window(CIW) for further processing. i. Create a New Library ii. Create Schematic Cell view. iii. Create the Symbol for schematic Cell view. iv. Create the test Cell view. v. Analog simulation by spectre
i) Procedure for Creating New Library. • File –New – Library • Name : Give name for ur library Ex: VLSILAB_EXP_1 • Enable Attach to an existing technology library, Click OK • Attach the library to the technology library gpdk045.Click OK ii) Create Schematic Cell view. • Go to 1st window i.e virtuoso(CIW) • File-New-Cell view • Setup the new file form Library: Select the one you a created. Cell : Give the experiment name Ex: Inverter View_Schematic Type: Schematic press OK • Add the required components from the libraries and make the connections.  Go to instance fixed menu or use shortcut key “I” from keypad to go instances  Click on browse. This opens the library browser  Now select the appropriate library for components like  Gpdk45 ------------------------nmos1v, pmos1v  Create Input and Output pins  Make the connections by using fixed narrow wire key  Click Check and Save button


![WhatsApp Image 2025-01-24 at 16 09 23_7e8d9eb7](https://github.com/user-attachments/assets/fd3a6d73-e14e-4dc9-8673-f8b053f779a8)


ii) Creating the Symbol for schematic Cell view • In the schematic window, execute  Create – Cell view – From Cell view  The cell view from cell view window appears  Check Lib Name, Cell Name, From View name must be schematic Press ok • Now Symbol generation form appears. Click Ok If No changes required • A new window with with default symbol is created. • Edit the symbol if you want to give actual symbol shape else continue. • Execute Create-Cell view-from cell view • Library Name and Cell Name must be same which you have used for schematic. Press OK • Check for the position of pin side.Prss OK • Edit for the shape by Create-Shape-Choose required options to edit.

Analog simulation by SPECTRE. • In test cell view window • Launch – ADE L(Analog Design Environment)  Execute Setup—Simulation/directory/Host A new window opens  Set the simulation window to spectre and click ok  Execute Analysis – Choose. A window opens.  Select the type and set the specifications and press OK  Execute Output s—to be plotted – Select on Schematic  Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse • Execute Simulation -- Net list and Run


![WhatsApp Image 2025-01-24 at 16 08 11_3d0b40a7](https://github.com/user-attachments/assets/a4f169d4-d858-4bf3-bc18-80b9756febb3)


Results:

The experiment successfully demonstrated the design and implementation of a 2:1 MUX using Cadence EDA tools.
The successful verification through schematic, layout, and simulation underscores the effectiveness of using Cadence EDA tools for digital circuit design.
