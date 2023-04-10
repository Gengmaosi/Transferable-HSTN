# Transferable-HSTN

The official implementation of the paper "Adaptive and simultaneous trajectory prediction for heterogeneous agents via Transferable hierarchical Transformer network." The abstract is "Simultaneously and accurately predicting trajectories of multiple heterogeneous agents is crucial for intelligent transportation systems (ITS) applications, e.g., connected and autonomous vehicles. Existing model-based and data-driven methods can achieve good prediction accuracy, but most of them neglect the domain shift issue and prevalent imperfect data problems, i.e., few-shot learning and zero-shot learning issues. To address these issues, we propose a multi-source transfer learning (TL) framework, transferable hierarchical Siamese Transformer network (T-HSTN), for trajectory prediction of multiple heterogeneous agents, e.g., vehicles, bicycles, and pedestrians, at urban unsignalized intersections under small data conditions. Specifically, by extending the self-attention mechanism and exploring feature representations of traffic scenes, a Transformer-based network that hierarchically extracts temporal/spatial and map features is introduced as the basic prediction model. Moreover, a TL framework with adaptive learning and feature alignment modules is built to explore the feature representations of unfixed traffic scenes and align both statistical and deep features to learn domain-invariant knowledge. More challenging trajectory prediction experiments are designed, corresponding to newly-built or badly-instrumented intersections under real-world scenarios. Experimental results verify the proposed method's high accuracy, transferability, and generability. Our work fills the gap in solutions and benchmarks for TL tasks in trajectory prediction for heterogeneous agents, and the conducted TL experiments provides a more practical setting of considering imperfect data problems in trajectory prediction."

# Note
Our paper is under the first round review of IEEE T-ITS. Once our paper is formally published, we will further release the data preprocess code.

# License
This repo is released under the MIT License. The T-HSTN framework was bulit on top of pytorch.

# Reference
The "multi_attention_forward.py" code base borrows from https://github.com/Majiker/STAR; The "Transformer_utils" code base borrows from https://github.com/decisionforce/mmTransformer.
