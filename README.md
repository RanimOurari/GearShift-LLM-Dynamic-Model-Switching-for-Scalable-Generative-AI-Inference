# GearShift-LLM-Dynamic-Model-Switching-for-Scalable-Generative-AI-Inference
This project studies GearShift LLM, a dynamic serving strategy that improves scalability by switching between a large, high-quality model (GPT-2) and a smaller, faster model (DistilGPT-2) based on system load.

## Objectives:
-Measure and model inference latency for different model sizes.

-Quantify the quality trade-off between large and small models.

-Simulate an online inference service with dynamic model switching.

-Optimize switching policies to minimize latency under quality constraints.

-Validate performance using an analytic M/G/1 queueing model.

## Methodology
The workflow follows a systems modeling pipeline:

-Offline latency measurement
-Statistical service-time modeling
-Predictive queueing analysis
-Online simulation of dynamic policies
-Optimization and policy selection
-Validation and visualization of trade-offs
