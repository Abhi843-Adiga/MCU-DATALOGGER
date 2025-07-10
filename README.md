MCU Data Logger (2-Layer & 4-Layer PCB Design) :        
-> A compact, modular microcontroller-based data logger designed using KiCad.         
-> This project includes both 2-layer and 4-layer PCB implementations managed through Git branching and git attributes.

Design Disclaimer :
These PCB designs are provided for educational purposes only.

Passed Checks:
The designs have successfully passed basic ERC (Electrical Rules Check) and DRC (Design Rule Check) in the KICAD.

Untested Aspects:
These designs have not been validated for advanced electrical performance.
Critical aspects that have not been analyzed or tested include:
->Signal Integrity (SI):High-speed signals (like SPI) have not been analyzed for reflections or timing issues.
->Power Integrity (PI):The power delivery network has not been simulated for stability.
->EMI/EMC:The design has not been tested for electromagnetic interference or compatibility. 

It will likely not pass regulatory certifications without further revisions.

Do not use these designs for a production-ready or commercial product without performing a thorough analysis and validation for SI, PI, and EMC.

Contributing:
If you have experience in SI/PI analysis, EMC hardening, or would like to improve the design, please feel free to fork the repository and submit a pull request.
