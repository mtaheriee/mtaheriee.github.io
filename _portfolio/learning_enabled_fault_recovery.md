---
title: "Learning-Enabled Fault-Recovery Control with Causality-Guided Adaptation"
excerpt: >
  A causality-guided neural control framework for actuator fault recovery, combining offline causal inference with selective online adaptation under Lyapunov stability guarantees.
  <br/><br/>
  <img src="/assets/images/research/causal_nn_fault_recovery.png" style="width:100%; max-width:600px;">
collection: portfolio
---

### Overview
As a Postdoctoral Scholar at Caltech, I developed **adaptive neural controllers** for nonlinear systems subject to **actuator loss-of-effectiveness (LOE) faults**.

### Key Idea
We introduced a **two-phase learning architecture**:
1. **Offline phase:**  
   Causal inference is used to identify the most **causally relevant layers** of a deep neural network-based fault compensator.
2. **Online phase:**  
   Only the selected layer is updated using a **Lyapunov-based gradient law** to guarantee bounded tracking error.

### Key Contributions
- First neural control framework with **causality-guided internal adaptation**
- Avoids unnecessary full-network retraining during fault recovery
- Preserves **formal stability guarantees** during online learning

### Case Study
Fault-recovery control of a **3-axis spacecraft attitude control system** under actuator faults.

This work demonstrates how learning can be embedded *inside* feedback loops without sacrificing safety.
