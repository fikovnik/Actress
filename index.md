---
layout: frontpage
title: The ACTRESS Modeling Environment
---

## About ##

To cope with evolving requirements and environmental conditions, software systems must be adaptive.
A common approach to developing self-adaptive systems is to architect them around feedback control loops (FCLs).
Advances have led to more explicit and safer design of some control architectures, however, there is a need for more integrated and systematic approaches that support end-to-end integration of FCLs into software systems.

We propose a tooled approach that provides researchers and engineers with flexible abstractions of FCLs allowing them to more easily integrate self-adaptation mechanisms into software systems.
It promotes separation of concerns whereby the development of system touchpoints, adaptation engine and the overall architecture can be decomposed and implemented by experts in the respective domains at different levels of abstraction.
It is based on a technologically agnostic domain-specific modeling language called Feedback Control Definition Language (FCDL).
It defines feedback architectures as hierarchically organized networks of adaptive elements, representing FCL processes such as monitoring, decision-making and reconfiguration.
The language is statically typed, handles composition and supports element distribution via location transparency.
Moreover it is reflective thereby enabling to coordinate and organize multiple control loops using different control schemes.
The use of the language is facilitated by an Eclipse-based modeling environment called ACTRESS.
It includes support for automated architecture consistency checking, and for code generation in which FCDL architectures are transformed into executable applications.
This provides a strong mapping between the control system design and its runtime implementation.

ACTRESS modeling environment built using [SIGMA](http://fikovnik.net/Sigma).

## Publications ##

* Filip Křikava, Philippe Collet, Robert France. "ACTRESS: Domain­Specific Modeling of Self­Adaptive Software Architectures" in Proceedings of the Proceedings of the 29th Symposium On Applied Computing (SAC) -­ Dependable and Adaptive Distributed Systems track, 2014

* Filip Krikava, Philippe Collet, Robert France. "Manipulating Models Using Internal Domain­Specific Languages" in Proceedings of the Proceedings of the 29th Symposium On Applied Computing (SAC) -­ Programming Language track, short­paper, 2014

* Filip Křikava, Philippe Collet. "On the Use of an Internal DSL for Enriching EMF Models" in Proceedings of the International Workshop on OCL and Textual Modelling 2012 (OCL), Innsbruck, September 2012. 

* Filip Křikava, Philippe Collet, Robert France. "Actor-based Runtime Model of Adaptable Feedback Control Loops" in Proceedings of the International Workshop on models@run.time 2012 (MRT), Innsbruck, September 2012.

* Filip Křikava, Javier Rojas Balderrame, Johan Montagnat, Philippe Collet. "Using Adaptation Strategies to Improve Grid Operations"  (short paper - poster), In EGI Technical Forum 2012, Prague, 17-21 September 2012.

* Filip Křikava, Philippe Collet. "Using Architecture Models to Rapidly Prototype Feedback Control Systems" (short paper - poster), In GDR GPL 2012, Rennes, 18-22 June 2012. 

* Filip Křikava, Philippe Collet. "A Reflective Model for Architecting Feedback Control Systems" To appear in Proceedings of the 23rd International Conference on Software Engineering & Knowledge Engineering (SEKE'2011), Miami Beach, USA, 7-9 July 2011.

* Filip Křikava, Philippe Collet, Mireille Blay-Fornarino. "Uniform and Model-Driven Engineering of Feedback Control Systems" (short paper – poster) in Proceedings of the 8th IEEE/ACM International Conference on Autonomic Computing (ICAC'2011) ACM, Karlsruhe, Germany, 14-18 June 2011.

## Acknowledgement ##

This work is partly funded by the [ANR SALTY project](https://salty.unice.fr/) under contract ANR-09-SEGI-012.

## Contact ##

ACTRESS is being developed by the [MODALIS](http://modalis.polytech.unice.fr/) team of [I3S Laboratory](http://www.i3s.unice.fr/I3S/) and [SPIRALS](https://team.inria.fr/spirals/) team of [INRIA Lille](http://www.inria.fr/en/centre/lille).

For further information, please contact:

* [Philippe Collet](http://www.i3s.unice.fr/~collet/)
* [Filip Křikava](http://fikovnik.net/canape/index.html)
* or visit [ACTRESS](https://github.com/fikovnik/Actress) github project
