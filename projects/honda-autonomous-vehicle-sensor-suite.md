# Design of a Sensor Suite for a Software-Defined Autonomous Vehicle Research Platform

## Source

- Original: [`raw/Honda_SmithDesignClinic_26-27_Sensor Suite_Project Summary_final.pdf`](../raw/Honda_SmithDesignClinic_26-27_Sensor%20Suite_Project%20Summary_final.pdf)
- Sponsor: Honda Research Institute USA, Inc. (HRI-USA / 99P Labs)
- Location: Columbus, Ohio
- Project period: September 2026–May 2027
- Program: Smith College Picker Engineering Program, Design Clinic

## Overview

The project will develop a comprehensive sensor suite for an electric golf cart being converted into a software-defined autonomous-vehicle research platform. The intended platform will support manual human driving, remote human teleoperation, and bounded autonomous operation. A separate capstone team is working on electronically controlled (x-by-wire) driver controls; the two teams are expected to coordinate on shared computing and communications infrastructure.

The sensor team's work includes researching and selecting sensors, designing mounts and connections, prototyping and calibrating the system, and establishing an initial framework for collecting, formatting, processing, and interpreting sensor data.

## Scope and work areas

- **Sensor selection:** Evaluate suitable technologies, including lidar, stereo cameras, GPS, radar, and inertial measurement units (IMUs); compare multiple commercially available options for each planned sensor type.
- **Positioning and integration:** Design and implement physical sensor mounting and connections on the golf cart.
- **Testing and calibration:** Test and calibrate sensors for functionality and reliability across environmental conditions.
- **Data processing:** Develop an initial framework to standardize and collect raw sensor data, and support its processing and interpretation.
- **Cross-team integration:** Coordinate with the x-by-wire team on a single-board computer (SBC) for centralized processing and communications, and a CAN bus for communication between drive-by-wire and sensor subsystems.

## Agentic AI workflow objective

The team will investigate multi-agent AI as an engineering design collaborator, including:

- Research and analysis of sensor technologies, safety features, and engineering literature; independent comparison of alternatives and documentation of evidence, conflicts, and assumptions.
- Constrained generative design exploration for items such as sensor mounts, brackets, enclosures, and component layouts.
- Support for requirements traceability, interface checks, test-case generation, and failure-mode brainstorming.

Students remain responsible for verifying sources and approving conclusions. AI-generated recommendations do not approve safety-critical designs; human review and conventional analysis, simulation, inspection, and physical testing remain authoritative. The team will document where agentic methods provide value and where they fail or require substantial human intervention.

## Deliverables and timing

| Deliverable | Target timing stated in source |
| --- | --- |
| Project scope and design requirements for the complete sensor suite (Scope memo) | Late September |
| Technical summary of sensors and detection technology relevant to autonomous vehicles (Technical Foundation memo) | Mid-October |
| Planned sensor list with multiple commercially available options for each sensor type (Design Review 2) | Design Review 2 |
| Proposed suite evaluation, including testing and calibration results (Design Review 4) | Mid-March |
| Complete sensor-suite prototype and engineering documentation, including test results, calibration data, electrical schematics, and bill of materials | End of Q4 |
| Reflection on agentic AI workflows (final report) | End of Q4 |

## Sponsor liaisons

- **Duane Detwiler** — Vice President, HRI/99P
- **Rajeev Chhajer** — Chief Engineer, Software-defined Intelligence Research; co-mentor
- **Ryan Lingo** — Applied AI Research Engineer and Developer Advocate; co-mentor

The source document includes liaison contact details.

## Background

The intended platform is a shared testbed for investigating how human and AI-based controllers perceive, decide, and act in controlled driving scenarios. Example measures named in the source include reaction time, stopping distance, trajectory selection, obstacle clearance, and intervention frequency. The project establishes the platform and representative comparisons; it is not intended to be a comprehensive human-subject research study.
