# Programming Digital Twins - pdt-exercise-docs

## Overview

This repository contains lab module directory structures and sample markdown files for use with the [Programming Digital Twins Kanban Board](https://github.com/orgs/programming-digital-twins/projects/1) exercises.

It is intended for student use to track markdown documentation for each lab module and to store relevant lab module configuration files (i.e., for the Edge Device App, or EDA).

### Project Objectives

The [LabBenchStudios-PDT-Unity](https://github.com/programming-digital-twins/LabBenchStudios-PDT-Unity) research project is intended to be used with this [pdt-exercise-docs](https://github.com/programming-digital-twins/pdt-exercise-docs) repository and has three primary objectives:

(1) Build a largely F/OSS Digital Twin framework that can work with other [Programming Digital Twins projects](https://github.com/programming-digital-twins) and their repositories to sync live data, DTDL models, and a JSON-based constraint mapping layer, and render within a COTS physics sim engine (e.g., Unity 6).

(2) Use a digital twin asset's configuration data to auto-generate a GPT AI prompt to query one or more locally running LLM's to retrieve predictive maintenance recommendations for the specific system within the Digital Twin environment.

(3) Provide a baseline technology platform for my Northeastern University College of Engineering graduate students (and me) to learn and experiment with various Digital Twin use cases.

### Helpful Links

PDT Kanban Board: [Programming Digital Twins Requirements](https://github.com/orgs/programming-digital-twins/projects/1)

Please see the following links for some helpful information about the PDT exercises and other associated repositories. Please note that many of the exercises and sample source code in this repository is based on some of the patterns and exercises from my book, [Programming the Internet of Things Book](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401/).
 - Programming Digital Twins (PDT) specific:
   - [Programming Digital Twins Exercises (aka PDT Kanban Board)](https://github.com/orgs/programming-digital-twins/projects/1)
   - [Programming Digital Twins - LBS PDT Unity Package](https://github.com/programming-digital-twins/LabBenchStudios-PDT-Unity/)
   - [Programming Digital Twins Client Framework Repository](https://github.com/programming-digital-twins/pdt-cfw-components)
   - [Programming Digital Twins Edge Components Repository](https://github.com/programming-digital-twins/pdt-edge-components)
   - [Programming Digital Twins Exercise Doc Templates Repository](https://github.com/programming-digital-twins/pdt-exercise-docs)
 - Other reading links:
   - [Programming the Internet of Things Exercises (aka PIOT Kanban Board)](https://github.com/orgs/programming-the-iot/projects/5)
   - [Programming the Internet of Things Book](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401/)

## Organization

- README.md: For each lab module, the student is expected to complete the README.md template with specific details pertaining to the given lab module.
- eda{number}.props: For each lab module, there will be one or more eda{number}.props configuration file(s). These will need to be edited by the student to reflect the requirements for the given lab module. For those lab modules that do not require updated EDA configurations, simply copy the previous lab mdoule config file(s) to the new lab module directory. This will ensure each lab module has the appropriate configuration for any running EDA needed for that lab module.

### labmodule01
- README.md
- eda001.props

### labmodule02
- README.md
- eda001.props

### labmodule03
- README.md
- eda001.props

### labmodule04
- README.md
- eda001.props

### labmodule05
- README.md
- eda001.props

### labmodule06
- README.md
- eda001.props

### labmodule07
- README.md
- eda001.props
- eda002.props

### labmodule08
- README.md
- eda001.props
- eda002.props
- eda003.props

### labmodule09
- README.md
- eda001.props
- eda002.props
- eda003.props

### labmodule10
- README.md
- eda001.props
- eda002.props
- eda003.props
- eda004.props
- eda005.props
