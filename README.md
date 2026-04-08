# Crystal-structure-visualizer
A simple and interactive 3D crystal structure visualizer built using JavaScript and Three.js.
This project allows users to explore basic crystal lattices like Diamond, Graphite, and NaCl, and also load custom CIF files.
________________________________________
 # Features
•	 3D visualization using Three.js
•  Interactive controls (rotate, zoom, pan)
•	 Built-in crystal structures:
o	 Diamond lattice
o	 Graphite lattice
o	 NaCl structure
•	 Load custom CIF (Crystallographic Information File)
•	 Automatic bond detection
•	 Unit cell visualization
•	 Atom labels (C, Na, Cl, etc.)
________________________________________
# Project Structure
project-folder/
│── index.html   # Main application file
│── README.md    # Project documentation
________________________________________
# How to Run
1.	Download or clone this project
2.	Open index.html in any modern web browser (Chrome recommended)
No installation or server required 
________________________________________
# Controls
Action	Input
Rotate	Mouse drag
Zoom	Mouse scroll
Pan	Right-click drag
________________________________________
# How to Load CIF Files
1.	Click "Choose File"
2.	Select a .cif file
3.	The structure will render automatically
   CIF files contain atomic coordinates used in Crystallography
________________________________________
 # Supported Structures
 Diamond
•	Based on diamond cubic structure
•	Each atom bonded to 4 neighbors
 Graphite
•	Layered hexagonal structure
•	Represents stacked Graphene sheets
 NaCl
•	Simple cubic ionic structure
________________________________________
# Limitations
•	Basic CIF parser (does not support full symmetry operations)
•	Uses approximate bond detection (distance-based)
•	Unit cell is simplified (cubic approximation)
________________________________________
# Future Improvements
•	 Full CIF parsing (loop_, symmetry operations)
•	 Supercell generation (repeat lattice)
•	 Better atom radii and colors
•	 GUI controls (sliders, toggles)
•	 Real lattice parameters (a, b, c, α, β, γ)
________________________________________
 # Technologies Used
•	HTML5
•	JavaScript
•	Three.js
________________________________________
# Acknowledgements
•	Three.js community
•	Open crystallography datasets
________________________________________

## Author 
name : sunil matwa 

reg.No. : 25BCE10466
