---
layout: frontpage
title: The ACTRESS Modeling Environment
---

## About ##

To cope with evolving requirements and environmental conditions, software systems must be adaptive. A common approach to developing self-adaptive systems is to architect them around feedback control loops (FCLs). While advances have led to more explicit and safer design of some control architectures, there is still a lack of comprehensive support for architecting both the control (decision making) and the integration (monitoring, reconfiguration) parts of FCLs into the targeted systems. To address this problem we provide a toolchain, ACTRESS, that enables software architects to design and integrate feedback control loops using model-driven engineering techniques. The toolchain relies on a reflective, fine-grained design and runtime modeling environment for feedback control architectures that permits us to build complex solutions with hierarchical layers of control loops. It consists of 

* a DSL to architect, reuse and program loop elements
* a support for verification using a variety of techniques that enables one to easily check different structural and behavioral properties on FCLs, and 
* an actor-oriented runtime environment.

The ACTRESS Modeling Environment captures an outgoing work towards the goal of providing a model-driven development toolkit for designing, implementing and validating adaptive behavior that can be added on a top of existing computing systems thus turning them into self-adaptive systems.
This toolkit gives system administrators, control theorists and other computer scientists building blocks that allows them to quickly prototype and test adaptation strategies and abstracts them from the painful low-level implementation details.

ACTRESS is a modeling environment built using [SIGMA](http://fikovnik.net/Sigma).

## Publications ##

* Filip Křikava, Philippe Collet. "On the Use of an Internal DSL for Enriching EMF Models" in Proceedings of the International Workshop on OCL and Textual Modelling 2012 (OCL), Innsbruck, September 2012. 

* Filip Křikava, Philippe Collet, Robert France. "Actor-based Runtime Model of Adaptable Feedback Control Loops" in Proceedings of the International Workshop on models@run.time 2012 (MRT), Innsbruck, September 2012.

* Filip Křikava, Javier Rojas Balderrame, Johan Montagnat, Philippe Collet. "Using Adaptation Strategies to Improve Grid Operations"  (short paper - poster), In EGI Technical Forum 2012, Prague, 17-21 September 2012.

* Filip Křikava, Philippe Collet. "Using Architecture Models to Rapidly Prototype Feedback Control Systems" (short paper - poster), In GDR GPL 2012, Rennes, 18-22 June 2012. 

* Filip Křikava, Philippe Collet. "A Reflective Model for Architecting Feedback Control Systems" To appear in Proceedings of the 23rd International Conference on Software Engineering & Knowledge Engineering (SEKE'2011), Miami Beach, USA, 7-9 July 2011.

* Filip Křikava, Philippe Collet, Mireille Blay-Fornarino. "Uniform and Model-Driven Engineering of Feedback Control Systems" (short paper – poster) in Proceedings of the 8th IEEE/ACM International Conference on Autonomic Computing (ICAC'2011) ACM, Karlsruhe, Germany, 14-18 June 2011.

## Acknowledgement ##

This work is partly funded by the [ANR SALTY project](https://salty.unice.fr/) under contract ANR-09-SEGI-012.

## Contact ##

ACTRESS is being developed by the [MODALIS](http://modalis.polytech.unice.fr/) team of [I3S Laboratory](http://www.i3s.unice.fr/I3S/).

For further information, please contact:

* [Philippe Collet](http://www.i3s.unice.fr/~collet/)
* [Filip Křikava](http://fikovnik.net/canape/index.html)
* or visit [ACTRESS](https://github.com/fikovnik/Actress) github project
