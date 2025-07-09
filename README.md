# PLL1 PCB Project
This project showcases the design and implementation of a Phase-Locked Loop (PLL1) circuit using KiCad8.0. It includes schematic design, PCB layout, and fabrication files. After generating the Gerber files, the board was fabricated and manually assembled. Prior to fabrication, functionality was verified using a perfboard prototype.

# Preview
## Assembled PCB  
[![Assembled PCB](media/pll1-real-board.jpg)](media/pll1-real-board.jpg)
## Prototype Testing on Perfboard  
[![Prototype Testing](media/ppl1-proto-board.jpg)](media/ppl1-proto-board.jpg)

# Project Structure

PLL1-PCB-Project/
├── src/
│   ├── PLL1.sch                  # Schematic file
│   ├── PLL1.kicad_pcb            # PCB layout
│   ├── PLL1.pro                  # KiCad project file
│   └── custom footprints/        # Custom footprint libraries
│
├── output/
│   ├── BOM.csv                   # Bill of Materials
│   ├── PickAndPlace.csv          # Component placement data
│   ├── pll1.drl                  # Drill file
│   ├── .gbr                     # Gerber fabrication files
│
├── media/
│   ├── pll1-real-board.jpg       # Final PCB image
│   └── ppl1-proto-board.jpg      # Perfboard prototype image
│
└── README.md                     # Project documentation
```

---

## Tools Used

- **KiCad 8.0** – for schematic and PCB design
- **Manual Soldering** – for component assembly
- **Perfboard Testing** – basic circuit verification before PCB fabrication

---

## Output Files

- **Bill of Materials (BOM)**
- **Pick-and-Place file**
- **Drill file**
- **Gerber files** (for PCB fabrication)

---

## Applications

- Educational exploration of PLL circuits  
- Hands-on experience with PCB design and manufacturing  
- Practice in manual soldering and prototyping


## Author
D.V.Mohith 
Electrical Engineering  
IIT Bhubaneswar  
GitHub: [dvmohith-66](https://github.com/dvmohith-66)

