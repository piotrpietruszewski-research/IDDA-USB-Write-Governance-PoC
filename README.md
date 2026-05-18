# IDDA USB Write Governance — Public PoC

Public-safe runtime demonstration showing repeatable reduction of write activity on physical USB media.

---

## Overview

This repository contains a controlled proof-of-concept comparing:

- RAW execution
- SIMPLE baseline filtering
- IDDA runtime optimization behavior

The goal of the experiment is to demonstrate observable reduction of write activity during repeated validation runs on identical USB devices.

This public release intentionally excludes protected runtime implementation details.

---

## Validation Setup

- 2 identical USB 3.0 devices
- Controlled synthetic runtime workload
- 10 validation runs
- 5000 samples per run
- Physical write execution on both devices

---

## Observed Results

| Metric | Result |
|---|---|
| SIMPLE reduction vs RAW | 50.00% |
| IDDA reduction vs RAW | 70.48% |
| Additional IDDA gain | 40.96% |

---

## Included Artifacts

- Public HTML evidence console
- Validation screenshots
- Runtime visualization captures
- Validation summaries
- Public-safe documentation

---

## Technical Interpretation

RAW execution records every generated block.

A simple filter reduces activity using one public comparison baseline.

IDDA demonstrates additional reduction of write activity through runtime optimization and execution stabilization behavior.

The reduction remained repeatable across all validation runs.

---

## Boundary Statement

This repository demonstrates observable runtime behavior only.

It is **not**:
- a production storage benchmark,
- a disk endurance certification,
- a universal hardware performance claim,
- or a production deployment package.

Internal execution logic, tuning policies and protected runtime details are intentionally excluded from the public release.

---

## License Scope

The Apache 2.0 license applies only to the public demonstration artifacts contained in this repository.

Protected runtime logic, internal execution mechanics, tuning policies and private research components are not included in the public release.

---

## Status

Research PoC / Runtime Demonstration

Public-safe release.
