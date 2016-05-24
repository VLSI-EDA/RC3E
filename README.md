# Reconfigurable Common Cloud Computing Environment (RC3E)

[![Documentation Status](https://readthedocs.org/projects/rc3e/badge/?version=latest)](http://rc3e.readthedocs.io/en/latest/?badge=latest)
![Latest tag](https://img.shields.io/github/tag/VLSI-EDA/RC3E.svg?style=flat)
[![Latest release](https://img.shields.io/github/release/VLSI-EDA/RC3E.svg?style=flat)](https://github.com/VLSI-EDA/RC3E/releases)
[![Apache License 2.0](https://img.shields.io/github/license/VLSI-EDA/RC3E.svg?style=flat)](LICENSE.md)


This software is published and maintained by **Chair for VLSI Design, Diagnostics and Architecture** - 
Faculty of Computer Science, Technische Universität Dresden, Germany  
**http://vlsi-eda.inf.tu-dresden.de**


<img src="https://raw.githubusercontent.com/VLSI-EDA/RC3E/master/docs/_static/images/logo_tud.jpg" width="300" />


## 1 Overview

Computing performance and scalability are essential ingredients in modern data centres offering cloud services. Field Programmable Gate Arrays (FPGAs) provide a promising opportunity to improve performance, security and energy efficiency because their hardware architecture can be adapted directly to the application.
 
We developed a special resource management system (RC3E) which serves as a hypervisor for reconfigurable hardware. In contrast to other approaches, we model the system as a whole with a more flexible FPGA provision. The application service provider has the opportunity to offer a service with an individual FPGA design or customized secure interfaces to the cloud. For an abstraction from the real hardware and to achieve high device utilization, the FPGAs and the interfaces are fully virtualized with our additional RC2F framework.

## 2 Components
* RC3E - Reconfigurable Common Cloud Computing Environment
* RC2F - Reconfigurable Cloud Computing Framework

## 3 Users and Service Models
A a major goal of the project is it to provide the resource FPGA to a wide range of different users. A provision of virtual FPGAs (vFPGA) can make the reconfigurable resource available for service providers who can accelerate their own specific services without interaction with their cloud providers or a data centre operator.

For a flexible integration of the reconfigurable hardware into our cloud we offer three service models:

* RSaaS - Reconfigurable Silicon as a Service
* RAaaS - Reconfigurable Accelerators as a Service
* BAaaS - Background Acceleration as a Service


