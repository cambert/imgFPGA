# imgFPGA

Welcome to the main development repository for `Image and Video Proceessing FPGA-based Development Platform`. 


The principle is to provide students / researchers with an open environment allowing them to concentrate on image / video processing algorithms when targeting  them for FPGA deveices. The aim is to:
- reduce the time required for system bring-up; 
- provide set of tools and system components to allow various tasks, such as loading images to FPGA and off-loading post processing data;
- unify platforms between researchers to allow easier benchmarking when comparing various algorithms;

The provided _envoronemnt_ shall invlude:
- basic set of files to allow project creasion for selected [fpga development boards](http://www.altera.co.uk/education/univ/materials/boards/de1-soc/unv-de1-soc-board.html);
- RTL code for various communication interfaces, e.g. UART, PS2, etc.;
- RTL controller for selected camera modules;
- TestBench to allow RTL testing and verification;
- Python scripts for various house-keeping and verification tasks, such as image file conversion to bitstream format suitable for convenient PC -> FPGA transfer for algorithm verification;




For further documentation please see [wiki pages](https://github.com/imgFPGA/imgFPGA/wiki).


### Useful links

[How to Latex in the cloud](https://www.sharelatex.com/)
[How do formatting in README](https://help.github.com/articles/markdown-basics/)


