# ACTRESS

To cope with evolving requirements and environmental conditions, software systems must be adaptive. A common approach to developing self-adaptive systems is to architect them around feedback control loops (FCLs). While advances have led to more explicit and safer design of some control architectures, there is still a lack of comprehensive support for architecting both the control (decision making) and the integration (monitoring, reconfiguration) parts of FCLs into the targeted systems. To address this problem we provide a toolchain, ACTRESS, that enables software architects to design and integrate feedback control loops using model-driven engineering techniques. The toolchain relies on a reflective, fine-grained design and runtime modeling environment for feedback control architectures that permits us to build complex solutions with hierarchical layers of control loops. It consists of 

* a DSL to architect, reuse and program loop elements
* a support for verification using a variety of techniques that enables one to easily check different structural and behavioral properties on FCLs, and 
* an actor-oriented runtime environment.
