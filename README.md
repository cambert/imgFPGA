<img src="https://cloud.githubusercontent.com/assets/11151121/6693644/656b4722-cccc-11e4-9581-82554ab09585.png" align="left" height="100" >


Welcome to the development repository for **Image and Video Processing FPGA-based Development Platform**. 

The principle is to provide students/researchers with an open HW/SW environment and platform allowing image/video processing algorithms development when targeting FPGA devices. The aim is to:
- minimize the time required for system bring-up; 
- unify platforms between researchers to allow easier benchmarking when comparing various algorithms;
- provide set of scripts to ease RTL testing and verification at higher abstraction level, e.g. feeding TB with jpg/png file, with output data also being converted to graphics format;
- provide set of system components and interfaces to enable PC <=> FPGA communication in order to transfer test vectors and off-load results for post processing analysis;


The provided _envoronemnt_ shall include:
- basic set of files to allow project creation for selected FPGA development boards, e.g. [DE1-SoC](http://www.altera.co.uk/education/univ/materials/boards/de1-soc/unv-de1-soc-board.html);
- RTL controller for selected camera modules, e.g. [C3188A](https://www.quasarelectronics.co.uk/Item/c3188a-digital-output-cmos-colour-camera-module-omnivision-ov7620);
- RTL code for various communication and control interfaces, e.g. UART, Ethernet, I2C, PS2, etc.;
- Top-level testbench (TB) to allow system testing and verification;
- Multiple test programs to verify system components as well as custom RTL;
- Python scripts for various house-keeping and verification tasks, such as image file to bitstream conversion;
- Comprehensive documentation to allow further maintainance;

For further documentation please see [wiki pages](https://github.com/imgFPGA/imgFPGA/wiki).

### Useful links

[How to Latex in the cloud](https://www.sharelatex.com/) | [How do formatting in README](https://help.github.com/articles/markdown-basics/) | [The inspiration - NetFPGA](https://github.com/NetFPGA/)
