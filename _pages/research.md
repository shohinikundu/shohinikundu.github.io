---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

 
The *Advanced VLSI Design and Test Group* is involved in a number of projects covering a large spectrum of Microarchitecture, 
Hardware Security, Neural Processing and VLSI Design and Test Research.

### Hardware Security

Our research focuses on a number of hardware security problems from  protection of crypotographic circuits from side-channel
attacks to securing hardware and hardware supported security protocols in the Internet of Things (IoT) devices, Cyber-Physical Systems (CPS), 
and special purpose hardware accelerators such as Neural Processing Units (NPU), which are attractive targets for attackers.
The integration of a tremendous number of devices into IoT and CPS brings in concerns for system security. 
Our research works focus on solutions for a secure, trustworthy, and reliable hardware underlying the information systems. 
We work on various multi-dimensional approaches to protect the microelectronic supply chain and enable counterfeit detection 
and avoidance. This includes novel approaches to design elements that enable authentication/attestation during design and 
throughout the product life cycle. Our research work also includes novel technology such as blockchain to enable provable 
evidence of device state and identity. 
We work on trustworthy hardware design and the interaction between security and reliability. We have published a number of 
papers recently on Physically Unclonable Functions (PUF). Our current research focuses on PUF and True Random Number 
Generators (TRNG). PUF and TRNG circuits rely on underlying device characteristics to generate random response. 
However, they rely on different properties of underlying circuits. PUF circuits are used for chip authentication. 
Their responses must be reliable and repeatable, implying that PUF response should be invariant to environmental factors 
such as voltage and temperature disturbances, yet they must vary from one fabricated device to the other implying that they 
must rely on physical variations. However, the response of the PUF circuit must not be a simple 
linear transformation of the physical variations which makes them vulnerable to modeling attacks. 
If they rely on non-linear transformation of physical variations, such transformations must be sufficiently 
complex to withstand modeling attacks. Even the verifier needs to be able to withstand cloning attacks. 
It must not send the same sequence of challenges for authentication, as the correct responses may be memorized 
by an attacker and used subsequently. Our PUF circuits rely on exploiting lithographic distortions while we design 
these circuits to be insensitive to voltage and temperature to improve uniqueness while also improving their reliability. 
Our research in security is expanding to include various forms of attacks and countermeasures. 
We are also exploring how to use/secure NVRAM for crypto applications. Stay tuned for publications in this area soon.

#### Defenses against attacks on NPU in Edge Devices

Machine-learned (ML) models are valuable storehouses of intellectual property (IP) 
requiring significant investment to develop. 
If such models can be cloned or transferred from another device easily, 
it presents a significant IP threat. 
Of concern is theft of machine learning IP from edge devices via semi invasive attacks, or purely
query based model cloning attacks. We are developing hardware supported solutions against model cloning attacks
with strong security guarantees, primarily targeting edge devices featuring neural processing units (NPU).


### Computer Architecture

On a broad level, our research interests are in path finding for efficient, resilient, and reliable architectures for the multicore era. 
Today’s designs are being shaped by the challenges of highly scaled technologies: stability and long-term reliability of devices, 
power dissipation limits that require dynamic adaptation of processor to computing needs. 
Our research in this area focuses on how to leverage the hardware and software abstraction layers of today’s systems to tradeoff performance, 
power and reliability in multicores. Several of the low level details of hardware such as power, thermal, and faults are tightly correlated 
to the hardware behavior, interactions within the system, and application behavior. The conventional approach to tackling such problems in hardware 
comes with additional costs and high design complexity. On the other hand, software based techniques are severely limited by observability 
and controllability into the hardware due to the strict abstraction layers of today’s systems. We propose multiple alternatives for dynamic 
adaptation of hardware. One such approach is based on a middleware call microvisor. The hardware provides the knobs and controls to monitor 
the low level details at a fine granular level, whereas, the microvisor manages actions for the threads running on the cores. Insulating 
management from the traditional software (including the operating system) enables a scalable, flexible and secure system level solution and 
allows the microvisor to evolve freely. Other alternatives include, dedicated controller for dynamic thread monitoring and rescheduling for 
both symmetric and asymmetric chip multiprocessors. We are also working on the design and evaluation of a novel hybrid NoC architecture which 
utilizes separate network topologies for real time and best effort traffic so as to achieve higher QoS while simplifying arbitration.

### VLSI CAD, Design Methodologies & Test

Our research in this area includes logic synthesis for emerging devices such as FinFETs, clocking and clock network design, 3D architectures, dynamic pattern generation for worst case power analysis, thermal simulation, lithography simulation, dual pattern lithography, optical proximity correction, lithographic error modeling, yield analysis, circuit reliability analysis, soft-error analysis, modeling of non-rectangular transistors and 3D devices. We have also explored suitability of GPGPUs for CAD algorithms. We have recently published a number of low-cost solutions for improving online error detection, diagnosis and repair that achieve nearly 100% coverage at about 15% energy overhead. We have a rich publication record in this area.
