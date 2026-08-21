# Vela-Hardware

## Project Summary

Vela-Hardware is reserved for Vela hardware-specific assets and integration
material. The repository currently contains only this README in the checked-in
workspace; no source files, tests, build manifests, board descriptions, device
drivers, or executable setup scripts were found during the repository scan.
That makes this leaf different from Vela-HAL, which contains the software
abstraction and protocol surface for device interfaces, and from Vela-OS,
which owns the image build system.

Because there is no implementation to inspect, this document intentionally
does not invent a board inventory, flashing process, pin map, sensor list, or
supported peripheral matrix. The other Vela leaves may reference QCS6490
hardware and attached accelerators, but those references are ecosystem
context, not implementation in this repository.

The feature table records the current evidence boundary. Every row has a
manual-review marker because no hardware or software behavior can be claimed
as manually verified from the repository alone. Future additions should include
a machine manifest, hardware revision and wiring documentation, supported
devices, provisioning instructions, and a repeatable smoke-test procedure with
expected observations.

The absence of files is itself the important current result of the scan. There
is no local command to build, flash, enumerate, calibrate, or exercise a board,
and no test fixture that could establish a hardware contract. Hardware facts in
Vela-HAL, Vela-OS, or other leaves should therefore be linked as dependencies,
not copied here as if this repository implemented them. A future contribution
should make ownership clear by naming the board revision, required instruments,
expected electrical or software observations, and the repeatable command or
procedure used to collect them.

## Feature Status

| # | Name / Description | Implemented? | Test Coverage? | Manual Test |
|---:|---|---|---|---|
| 1 | Hardware asset inventory | Planned | No tests found | [ ] Manual verification required |
| 2 | Board and hardware revision manifest | Planned | No tests found | [ ] Manual verification required |
| 3 | Pin, connector, and wiring documentation | Planned | No tests found | [ ] Manual verification required |
| 4 | Supported peripheral matrix | Planned | No tests found | [ ] Manual verification required |
| 5 | Flashing/provisioning procedure | Planned | No scripts or tests found | [ ] Manual verification required |
| 6 | Hardware smoke-test procedure | Planned | No tests found | [ ] Manual verification required |
| 7 | Device calibration or manufacturing data | Unknown | No implementation evidence found | [ ] Manual verification required |
| 8 | CI or hardware-in-loop integration | Unknown | No CI/test artifacts found | [ ] Manual verification required |

## Useful Validation

There are no repository-local build or test commands at present. Any future
procedure should document required equipment, target identifier, and expected
result.
