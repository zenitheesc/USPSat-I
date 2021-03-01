


<h1 align="center" style="color:white; background-color:black">USP Sat-AE1</h1>
<h4 align="center">This is an Open Hardware and Software cubesat developed by Zenith EESC-USP for the Cubedesign 2019.</h4>

<p align="center">
	<a href="http://zenith.eesc.usp.br/">
    <img src="https://img.shields.io/badge/Zenith-Embarcados-black?style=for-the-badge"/>
    </a>
    <a href="https://eesc.usp.br/">
    <img src="https://img.shields.io/badge/Linked%20to-EESC--USP-black?style=for-the-badge"/>
    </a>
    <a href="https://github.com/zenitheesc/USPSat-AE1/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/zenitheesc/USPSat-AE1?style=for-the-badge"/>
    </a>
    <a href="https://github.com/zenitheesc/USPSat-AE1/issues">
    <img src="https://img.shields.io/github/issues/zenitheesc/USPSat-AE1?style=for-the-badge"/>
    </a>
    <a href="https://github.com/zenitheesc/USPSat-AE1/commits/main">
    <img src="https://img.shields.io/github/commit-activity/m/zenitheesc/USPSat-AE1?style=for-the-badge">
    </a>
    <a href="https://github.com/zenitheesc/USPSat-AE1/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/zenitheesc/USPSat-AE1?style=for-the-badge"/>
    </a>
    <a href="https://github.com/zenitheesc/USPSat-AE1/commits/main">
    <img src="https://img.shields.io/github/last-commit/zenitheesc/USPSat-AE1?style=for-the-badge"/>
    </a>
    <a href="https://github.com/zenitheesc/USPSat-AE1/issues">
    <img src="https://img.shields.io/github/issues-raw/zenitheesc/USPSat-AE1?style=for-the-badge" />
    </a>
    <a href="https://github.com/zenitheesc/USPSat-AE1/pulls">
    <img src = "https://img.shields.io/github/issues-pr-raw/zenitheesc/USPSat-AE1?style=for-the-badge">
    </a>
</p>

The project was based on distributed processing architecture and using microcontrollers with ARM architecture. The Embedded System was composed by six subsystems:

<a href="https://github.com/zenitheesc/USPSat-AE1/tree/master/M%C3%B3dulo_Ribatski%20v.1.0"><h2>1. Thermal management</h2></a>

<p align = "center">
<img src="https://raw.githubusercontent.com/zenitheesc/Zenith-Wiki/gh-pages/assets/images/thermmgn.jpg"/>
</p>

This subsystem is primarily responsible for
for the active thermal control of the batteries, as proposed by the competition,
in addition to supporting the deployment system of the nanosatellite antennas.

<a href="https://github.com/zenitheesc/USPSat-AE1/tree/master/Varela-Logical_EPS%20v.1.0"><h2>2. Logical EPS</h2></a>
<p align = "center">
<img src="https://raw.githubusercontent.com/zenitheesc/Zenith-Wiki/gh-pages/assets/images/eps2.jpg"/>
</p>

Ensures the monitoring and control of EPS panel parameters,
that is, it performs the measurement of voltage and current levels at various points on the CubeSat;
monitors the temperature of the batteries and acts to keep it always positive, in addition to
carry out communication with other subsystems.

<a href="https://github.com/zenitheesc/USPSat-AE1/tree/master/London-Power_EPS%20v.1.1"><h2>3. Power EPS</h2></a>

<p align = "center">
<img src="https://raw.githubusercontent.com/zenitheesc/Zenith-Wiki/gh-pages/assets/images/eps1.jpg"/>
</p>

<a href="https://github.com/zenitheesc/USPSat-AE1/tree/master/Caurin_CDH%20v.1.0"><h2>4. Comanding and Data Handling</h2></a>

<p align = "center">
<img src="https://github.com/zenitheesc/Zenith-Wiki/blob/gh-pages/assets/images/comm.jpg?raw=true"/>
</p>

It concentrates one of the processing within CubeSat. It is responsible for managing the information
present in the prototype's internal network, by managing the information received and sent to the Control Base and control of the deployment of the antennas.

<a href="https://github.com/zenitheesc/USPSat-AE1/tree/master/Comin_CTR%20v.1.0"><h2>5. Computational Vision</h2></a>

<p align = "center">
<img src="https://github.com/zenitheesc/Zenith-Wiki/blob/gh-pages/assets/images/process.jpg?raw=true"/>
</p>
It concentrates one of the
processing within CubeSat. It is responsible for managing the information
present in the prototype's internal network, by managing the information received
and sent to the Control Base and control of the deployment of the antennas.

<a href="https://github.com/zenitheesc/USPSat-AE1/tree/master/Alves_ADC%20v.1.0"><h2> 6. Attitude Control </h2></a>

<p align = "center">
<img src="https://github.com/zenitheesc/Zenith-Wiki/blob/gh-pages/assets/images/ctr.jpg?raw=true"/>
</p>

The entire stabilization and pointing system must be done necessary to fulfill the competition missions. For this, the reading is done necessary sensors, activating a reaction wheel, which, by means of the Law of
Conservation of Angular Momentum, manages to act in the attitude of the satellite.

## 7. Structures

<p align = "center">
<img src="https://github.com/zenitheesc/Zenith-Wiki/blob/gh-pages/assets/images/str.jpg?raw=true"/>
</p>


Finally, we have the subsystem responsible for the physical integration of all
the subsystems described earlier. All manufacturing issues involving
the physical structure of USPSat is the responsibility of the structures subsystem. THE
determination of the materials used, the choice of manufacturing processes and display of all components, aiming at a satisfactory performance in the
vibration, are the main focuses of this subsystem

## Official Documentation

Check out the official documentation [here](https://github.com/zenitheesc/USPSat-AE1/blob/master/USPSat_Report.pdf).

<p align = "center">
<img src="https://github.com/zenitheesc/Zenith-Wiki/blob/gh-pages/assets/images/20190706_203958.jpg" alt="drawing" width="300" align="center"/>

<img src="https://github.com/zenitheesc/Zenith-Wiki/blob/gh-pages/assets/images/20190722_043926.jpg" alt="drawing" width="300" align="center"/>
</p>


<p align="center">
    <a href="http://zenith.eesc.usp.br">
    <img src="https://img.shields.io/badge/Check%20out-Zenith's Oficial Website-black?style=for-the-badge" />
    </a> 
    <a href="https://www.facebook.com/zenitheesc">
    <img src="https://img.shields.io/badge/Like%20us%20on-facebook-blue?style=for-the-badge"/>
    </a> 
    <a href="https://www.instagram.com/zenith_eesc/">
    <img src="https://img.shields.io/badge/Follow%20us%20on-Instagram-red?style=for-the-badge"/>
    </a>

</p>
<p align = "center">
<a href="zenith.eesc@gmail.com">zenith.eesc@gmail.com</a>
</p>
