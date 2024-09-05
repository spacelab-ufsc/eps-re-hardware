<h1 align="center">
	RELIABILITY ENHANCED ELECTRICAL POWER SYSTEM (RE²PS) HARDWARE
	<br>
</h1>

<p align="center">
    <a href="https://github.com/spacelab-ufsc/spacelab#versioning"><img alt="Static Badge" src="https://img.shields.io/badge/status-in_development-red"></a>
    <a href="https://github.com/spacelab-ufsc/eps-re-hardware/releases"><img alt="GitHub Release" src="https://img.shields.io/github/v/release/spacelab-ufsc/eps-re-hardware"></a>
    <a href="https://github.com/spacelab-ufsc/eps-re-hardware/commits/master"><img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/spacelab-ufsc/eps-re-hardware"></a>
    <a href="https://github.com/spacelab-ufsc/eps-re-hardware/issues"><img alt="GitHub Issues or Pull Requests" src="https://img.shields.io/github/issues/spacelab-ufsc/eps-re-hardware"></a>
    <a href="https://github.com/spacelab-ufsc/eps-re-hardware/pulls"><img alt="GitHub Issues or Pull Requests" src="https://img.shields.io/github/issues-pr/spacelab-ufsc/eps-re-hardware"></a>
    <a href="https://github.com/spacelab-ufsc/eps-re-hardware/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/spacelab-ufsc/eps-re-hardware"></a>
</p>

<details>
    <summary><b>Summary</b></summary>
    <ol>
        <li>
            <a href="#overview">Overview</a>
        </li>
        <li>
            <a href="#repository-organization">Repository Organization</a>
        </li>
        <li>
            <a href="#license">License</a>
        </li>
        <li>
            <a href="#releases">Releases</a>
        </li>
        <li>
            <a href="#notes">Notes</a>
        </li>
        <li>
            <a href="#references">References</a>
        </li>
    </ol>
</details>

## Overview
The PCB of **RE²PS** [[1]](#1) was designed to be more reliable than previous EPS models developed by SpaceLab. To achieve this, ECSS standards for PCB development in space environments were tailored for the project [[2]](#2). Some flexibility was applied in selecting new connectors for interfacing with other modules, but whenever possible, previously used connectors, such as Pico-Locks and PicoBlades, were chosen.

<p align="center">
    <img src="https://github.com/spacelab-ufsc/eps-re-hardware/blob/main/outputs/eps-re_2D_top.svg"><img src="https://github.com/spacelab-ufsc/eps-re-hardware/blob/main/outputs/eps-re_2D_bottom.svg">
</p>

<p align="center">
    <img src="https://github.com/spacelab-ufsc/eps-re-hardware/blob/main/outputs/eps-re_3D_top.png"><img src="https://github.com/spacelab-ufsc/eps-re-hardware/blob/main/outputs/eps-re_3D_bottom.png">
</p>

<p align="center">
    <a href="https://github.com/spacelab-ufsc/eps-re-hardware/issues/new?labels=bug"><img alt="Static Badge" src="https://img.shields.io/badge/Report_a_bug-red"></a>
    <a href="https://github.com/spacelab-ufsc/eps-re-hardware/issues/new?labels=enhancement"><img alt="Static Badge" src="https://img.shields.io/badge/Request_a_feature-yellow"></a>
    <a href="https://github.com/spacela-ufsc/eps-re-hardware/issues/new?labels=question,help+wanted"><img alt="Static Badge" src="https://img.shields.io/badge/Request_more_information_or_help-green"></a>
</p>

## Repository Organization
`sources`: Main files of the RE²PS's hardware project.

`outputs`: Output files, such as figures of the RE²PS's PCB, schematics, BOM and more.

## License
This project is open-source under the following license: CERN Open Hardware License v2.0.

## Releases

Releases are published after  ensuring that the project itself do not have any major errors and after testing the PCB. Please refer to the **documentation** for more details.

## Notes
For more info about the SpaceLab, access our [GitHub](https://github.com/spacelab-ufsc/spacelab), [Linkedin](https://br.linkedin.com/company/spacelab-ufsc) or our [website](https://spacelab.ufsc.br/en/home/).

## References
<a id="1">[1]</a> D. L. Figueiredo, "Reliability Enhanced Electrical Power System for Nanosatellites," in <i>Repositório Institucional da UFSC</i>, pp. 1-85, 2023, available at <a href="https://repositorio.ufsc.br/bitstream/handle/123456789/247559/PEEL2103-D.pdf?sequence=1&isAllowed=y"> this link</a>.

<a id="2">[2]</a> C. A. Rigo, L. O. Seman, M. D. Berejuck and E. A. Bezerra, "Printed Circuit Board Design Methodology for Embedded Systems Targeting Space Applications," in IEEE Latin America Transactions, vol. 18, no. 02, pp. 257-264, 2020, available at <a href="https://ieeexplore.ieee.org/document/9085278"> this link</a>.
