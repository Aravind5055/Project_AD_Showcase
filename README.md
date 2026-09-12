# 2.5D Chiplet Package Process Window Showcase

This repository presents selected visual results from a Python-based,
reduced-order engineering study of a representative 2.5D chiplet package. The
private development project connects chiplet placement, thermal response, a
thermo-mechanical screening proxy, manufacturing-risk indicators, design of
experiments, statistical diagnostics, Pareto tradeoffs and a multi-constraint
process window.

![Representative package architecture](assets/package_architecture.png)

## Engineering question

How can early package-design choices be screened transparently before detailed
finite-element analysis, supplier design-rule checks and physical
qualification?

The study explores five first-order levers:

- Chiplet placement scale
- Thermal-interface-material conductivity
- Silicon-interposer thickness
- Total chiplet power scale
- Microbump pitch

The parameters were selected because they represent geometry, thermal
performance, mechanical/handling sensitivity, operating load and interconnect
density. The framework deliberately limits the first model to explainable
variables connected to implemented responses.

## Selected results

The representative baseline contains six chiplets on a silicon interposer and
organic substrate. The current screening model reports a 60.16 degC peak
temperature, 2.936 MPa maximum stress proxy, 0.189 maximum comparative
manufacturing-risk score and 215 weighted-mm routing metric.

![Process-window map](assets/process_window.png)

The illustrated 441-point process-window study classifies 172 points as
acceptable, 206 as high risk and 63 as invalid geometry under the project's
illustrative constraints.

![Pareto trade space](assets/pareto_trade_space.png)

## Claim boundary

This is an educational, reduced-order comparative study. It is not thermal or
structural FEA, detailed routing, production-yield prediction, a foundry or
OSAT process design kit, or qualification evidence. Production use requires
technology-specific rules, calibrated material data, measured process
distributions, detailed multiphysics analysis and physical test-vehicle
correlation.

## Public contents

- Three selected engineering figures
- One-page portfolio poster
- This high-level project summary
- Copyright and usage notice

The implementation source, editable configuration, raw result tables, detailed
report and private collaboration history are intentionally not published.

## Author

Project maintained by [Aravind5055](https://github.com/Aravind5055).
