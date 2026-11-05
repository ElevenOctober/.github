# Project standard

An official project should be traceable to an accepted problem and should leave enough information for someone else to inspect, build, test, or reproduce the work.

## Project record

A project README or linked documentation should cover:

- Problem and its source
- Context, requirements, and constraints
- Prior work and references
- Architecture and implementation
- Testing methods, results, and failures
- Limitations and known failure modes
- Reproduction steps
- Repository and article
- Contributors and attribution
- License

Use the standard provenance record from the [problem lifecycle](PROBLEM_LIFECYCLE.md).

## Reproducibility

Include the versions, settings, tools, equipment, units, operating conditions, and required files that materially affect the result. Keep measured data and build instructions with the project where possible. State what is unknown or unavailable.

For hardware work, include where applicable:

- Schematics and editable PCB files
- Bill of materials with part identifiers and acceptable substitutions
- Firmware and source code
- Datasheets and mechanical CAD
- Assembly and test instructions
- Measurement data, photographs, and known failure modes

Do not call a hardware project open source unless the editable design sources needed to study, modify, and reproduce it are actually published. The [Open Source Hardware Definition](https://www.oshwa.org/definition/) describes documentation and design-source expectations.

## Safety and licensing

Identify electrical, mechanical, thermal, chemical, privacy, and other relevant risks. Do not test beyond the team’s competence or omit oversight where incorrect operation could cause serious harm.

Do not accept work involving weapons, harmful surveillance, credential theft, malware, unlawful access, unsafe medical devices, or dangerous electrical systems beyond the team’s competence. Work with serious physical risk requires qualified oversight and a clear validation plan.

Respect the license of every dependency and source. State a clear license for each project; the license for this community repository does not apply to separate project repositories.
