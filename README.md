Link: https://cad.onshape.com/documents/37fd5a85f79ebe20a6029276/w/db3c2ffc712adf7ef06de7c5/e/88f673a97a289337726580ef?renderMode=0&uiState=6ad8d7fe5b5abcf9bb015cb8
# Keyboardey

A weird keyboard CAD & Hardware design created for Half-Life.
[![View PCB on KiCanvas](https://hack.club/pcb-badge)](https://kicanvas.org/?repo=https://github.com/ViratS-best/Keyboardey/tree/main)

## Overview

Keyboardey is a weird, funky, custom-designed keypad layout built entirely from scratch. This project was my second time ever using CAD, making it quite a large learning curve in learning how to design mechanical parts, shape custom keys, etc. I also designed a PCB to go along with this project!

# Cad

<img width="690" height="463" alt="image" src="https://github.com/user-attachments/assets/2b7441a8-2f03-426c-8285-0e915d5e769d" />

I also had to create a custom cutout extrude to position keys correctly!

<img width="690" height="486" alt="image" src="https://github.com/user-attachments/assets/550efd5f-64b6-4aac-9129-da11a90b79ef" />

PCB and Case on Onshape (This was when I didn't know that I would actually have to change key chapes, and cutout shape):
<img width="1129" height="476" alt="image" src="https://github.com/user-attachments/assets/50e0cd9d-3e2d-4102-8f99-b2fc0a5adfeb" />


## Project Structure

```text
|── README.md
|── KEYBOARDEY.kicad__pcb
|── KEYBOARDEY.kicad__prl
|── KEYBOARDEY.kicad__pro
|── KEYBOARDEY.kicad__sch
|── KEYBOARDEY.step
```

# PCB
I decided to not use a module microcontroller but rather build one myself:
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/1c14f7cf-345a-4a13-8b0f-7699ab9020c4" />


Then I added the keyboard matrix:

<img width="562" height="576" alt="image" src="https://github.com/user-attachments/assets/b25c4853-076a-4c5b-9d8f-477f811b69ba" />

Finished MCU schematic:
<img width="890" height="411" alt="image" src="https://github.com/user-attachments/assets/a84cc5a9-d2d8-4366-b00d-d3318192936b" />

Routing & Placement:
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/a5db5494-f201-479b-88d4-d5849f6ce2fc" />


