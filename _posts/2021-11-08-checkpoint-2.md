---
title: "Progress report - November 11: Checkpoint #2"
date: 2021-11-07 16:41:55 +/-0800
categories: [Updates, "Checkpoint"]
tags: [updates,checkpoint]     # TAG names should always be lowercase
---

# Summary since October 7 Checkpoint #1  

### Progress Summary

The version 1 of the implementation showcased on October 7 - Checkpoint #1 now has several fixes and changes with regards to the translator functionality with conformance to the OpenQASM 3.0 specification.  Here are a few changes summarized on the v1 implementation: <br>
  -  Type system flaws identified and fixed in conformance to specification <br>
  -  Implementations for quantum and classical registers now robust in aliasing.<br>
  -  Initial implementation of 'duration' as per specification <br>
  -  Cleanup and reconciling minor changes that further strengthen stricter conformance to implementation according to specification. <br>

### Contribution Summary:

- [PR #295](https://github.com/Qiskit/openqasm/pull/295) : Suggestion to add Scope for power operator for complex types in language specification. Discussions taken up at TSC meeting. Discussions of requirement of dot notation of complex numbers for few rare use case implementations. <br>
- [Issue #296](https://github.com/Qiskit/openqasm/issues/296) : Following discussion with @taalexander at IEEE Quantum Week on OpenPulse grammar implementation and Jacks further discussions, team is now added to the openpulse closed group for discussion with guidance from people and teams working on OpenPulse. <br>
- [PR #269](https://github.com/Qiskit/openqasm/pull/269) : PR merged this month. Team contributed to bug and implementation fixes for merged reference AST implementation. <br>
- [Issue #304](https://github.com/Qiskit/openqasm/issues/304)  :  Bug report for openqasm3 pyPI package. <br>
- Presented progress and project overview at Qiskit advocate session at IEEE Quantum Week 2021. <br>

### Goals and further direction:

- Reconstruct and restart current repository to depend on openqasm package rather than forks of openqasm repository and outsource package dependencies for openasm parser, ast and other components
- Work in support of PR #295 and fulfillment of Issue #296.
- Take inspirations from discussions in Issue #296 and start writing to invent own grammar and connect it to openpulse, eventually towards an implementation for translating to qiskit-pulse/ qiskit-pulse builder syntax.
- Take opinions and hints from openpulse invested parties in the discussion in Issue #296 while creating it along. Have received guidance support from openpulse closed group

# Checkpoint \#2 Document <br>  
<object data="/assets/pdf/QAMPCheckpoint2.pdf" width="800" height="1000" type='application/pdf'></object>
