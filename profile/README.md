# Landing-page

# Renesas Electronics on GitHub

Welcome to the official GitHub presence of Renesas Electronics.

This page is the main entry point to Renesas public software resources on GitHub. It is designed to help developers quickly navigate across our software offer, find the right starting point for their device family, and access the relevant repositories, documentation, examples, and support resources.

Renesas provides a broad software ecosystem spanning microcontrollers, microprocessors, tools, middleware, RTOS integrations, AI enablement, and reference software. This page organizes that offer in a simpler and more discoverable way.

Whether you are evaluating a new device, looking for board support, searching for software examples, exploring open-source resources, or trying to understand where to begin, this page is intended to guide you to the right location.

---

This page provides a structured overview of the public software resources available for the Renesas **RA MCU family**, including:

- **Flexible Software Package (FSP)**
- **Example Projects**
- **Application Projects**
- **Documentation**
- **Releases**
- **Security / TrustZone / MCUboot resources**
- **AI / Edge AI resources**
- **Selected RA-related ecosystem repositories**

This repository is intended to help developers quickly find the right starting point depending on their board, feature, or workflow.


## Overview

The public software offer for Renesas RA MCUs is centered on two main repositories:

### 1. Flexible Software Package (FSP)
The **FSP** repository is the primary software foundation for RA MCUs. It provides drivers, middleware, RTOS integration, development support, release assets, and links to official documentation.

**Repository:**  
[renesas/fsp](https://github.com/renesas/fsp)

### 2. RA Example Projects and Application Projects
The **ra-fsp-examples** repository provides public:
- **Example Projects** for basic peripheral and middleware usage
- **Application Projects** for more complete solutions and reference implementations

**Repository:**  
[renesas/ra-fsp-examples](https://github.com/renesas/ra-fsp-examples)

---

## Start Here by Goal

## I want to start a new RA project
Recommended flow:

1. Review the [RA Product Page](https://www.renesas.com/us/en/products/microcontrollers-microprocessors/ra-cortex-m-mcus)
2. Go to the [RA Flexible Software Package (FSP) page](https://www.renesas.com/en/software-tool/ra-flexible-software-package-fsp)
3. Open the [RA FSP Documentation](https://renesas.github.io/fsp/)
4. Browse [RA Example Projects](https://github.com/renesas/ra-fsp-examples/tree/master/example_projects)

---

## I want example projects for a board or peripheral
Start with:

- [RA Example Projects Root](https://github.com/renesas/ra-fsp-examples/tree/master/example_projects)
- [RA Example Project Releases](https://github.com/renesas/ra-fsp-examples/releases)

A strong public showcase path is:

- [EK-RA8P1 Example Projects](https://github.com/renesas/ra-fsp-examples/tree/master/example_projects/ek_ra8p1)

This board path includes a wide range of public examples across storage, networking, USB, graphics, AI, low power, memory, security, camera, and display features.

---

## I want reference applications / full project examples
Start with:

- [RA Application Projects Root](https://github.com/renesas/ra-fsp-examples/tree/master/application_projects)

This area contains larger application and solution-oriented projects that complement the lower-level example projects.

---

## I want TrustZone, security, or secure boot examples
Start with:

- [RA Arm TrustZone Example Project Quick Start Guide](https://github.com/renesas/ra-fsp-examples/blob/master/example_projects/ra-arm-trustzone-ep-qsg.pdf)
- [EK-RA6M4 TrustZone Examples](https://github.com/renesas/ra-fsp-examples/tree/master/example_projects/ek_ra6m4/trustzone)
- [EK-RA8D2 TrustZone README](https://github.com/renesas/ra-fsp-examples/blob/master/example_projects/ek_ra8d2/trustzone/doc/readme.txt)
- [RA6 Booting Encrypted Image using MCUboot and QSPI](https://github.com/renesas/ra-fsp-examples/tree/master/application_projects/r11an0567/RA6_Booting_Encrypted_Image_using_MCUboot_and_QSPI)

These are good public entry points for:
- TrustZone evaluation
- secure / non-secure build flows
- MCUboot-based secure boot flows
- encrypted boot and external memory related examples

---

## I want AI / Edge AI resources for RA8
Start with:

- [renesas/ruhmi-framework-mcu](https://github.com/renesas/ruhmi-framework-mcu/tree/main)
- [RUHMI Releases](https://github.com/renesas/ruhmi-framework-mcu/releases)

Featured RA8P1 examples:

- [Face Detection Example](https://github.com/renesas/ruhmi-framework-mcu/tree/main/application_examples/face_detection)
- [Image Classification Example](https://github.com/renesas/ruhmi-framework-mcu/tree/main/application_examples/image_classification)

These examples demonstrate AI deployment flows on Renesas RA platforms using the RUHMI Framework.

---

## I want graphics or display-related public components
Start with:

- [renesas/libdave2d](https://github.com/renesas/libdave2d)

For broader board-level public graphics and display examples, browse:

- [RA Example Projects Root](https://github.com/renesas/ra-fsp-examples/tree/master/example_projects)
- [EK-RA8P1 Example Projects](https://github.com/renesas/ra-fsp-examples/tree/master/example_projects/ek_ra8p1)
