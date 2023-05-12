# STILL IN DEVELOPMENT
# Celeste Handheld
This project was made to emulate PICO-8 Celeste on a handheld device. Initially, the project was developed\
on a tm4c, but we decided it would be more cost-effective to build it on a different chip. Thus, we chose the\
SAMD21E17 because it met our requirements and was extremely. Furthemore, its built in DAC eliminated the \
need for a physical DAC.

## Getting Started
We used the [Segger Embedded Studio IDE](https://www.segger.com/products/development-tools/embedded-studio/) for our development. To get started, download the IDE and download the SAMD21 package from the package manager.\
If you are new to this environment, follow these step-by-step instructions:
1. Tools->Package Manager-> and search `SAMD21 CPU Support` and download the package
2. Clone the repository [here](https://github.com/thekevalian/CelesteHandheld).  If you're unfamiliar with git, try entering the directory that you\
want this project to be in using the  `cd` command in powershell. Then type\
 ``git clone https://github.com/thekevalian/CelesteHandheld --recurse-submodules``
3. Open the project in the `SW` folder

In the `SW` folder you will find all the software, other than that provided by the SAMD21 CPU Support. In the `Datasheets and Libraries` folder, you will find 3D models and footprints of the components used (provided by MOUSER). You will also find the CAD files associated with the shell of the handheld and a Bill of Materials.
