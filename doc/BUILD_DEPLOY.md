# Vela-Hardware Build and Deployment

## Purpose and scope

This leaf is reserved for Vela hardware-specific assets and integration
material. The checked-in repository currently contains only `README.md`; it
has no Makefile, source, tests, package manifest, board manifest, Docker/KAS/
CMake configuration, or executable deployment script.

## 1. Prerequisites

There are no repository-defined prerequisites. Any future procedure must name
the board revision, power and cabling requirements, host tools, instruments,
permissions, and target connection method before it can be reproduced.

## 2. Setup

No setup command is defined. Do not infer a board, pin map, driver, calibration
file, or provisioning layout from the neighboring Vela-HAL or Vela-OS leaves;
those are separate ownership boundaries.

## 3. Build and compile

No build or compile command exists because this repository contains no build
manifest or source implementation.

## 4. Tests and lint

No test or lint target exists. There are no repository-local tests or static
analysis configurations to run.

## 5. Packaging and artifacts

No packaging target or artifact directory is defined. No firmware, board
description, calibration data, driver, or release artifact is checked in.

## 6. Deployment, install, and run

No install, flash, provisioning, or run command exists in this leaf. Hardware
operations must wait for a checked-in, reviewable procedure that identifies the
target and expected result.

## 7. Cleanup

No cleanup target or generated output is defined.

## 8. Hardware, cloud, and manual verification caveats

Every hardware claim is currently manual and external to this repository. A
future implementation should add a machine-readable inventory, board/hardware
revision manifest, wiring and supported-peripheral matrix, repeatable smoke
test, and recovery procedure. Vela-HAL and Vela-OS may provide related software
workflows, but they do not establish a build or deployment workflow here.