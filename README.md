# Learning Barrier Certificate for monotone systems

This repository contains the code for the paper:

**"Neural Barrier Certificates for Monotone Systems"**,  
by Amirreza Alavi, Alireza Nadali, Majid Zamani, Saber Jafarpour


IEEE Control Systems Letters (L-CSS) / IEEE Conference on Decision and Control (CDC)

📄 **Paper:**  https://saberjafarpour.github.io/monotonebarrier.pdf

✉️ **Contact:** seyedamirreza.alavi@colorado.edu

🏢 **Affiliation:** University of Colorado Boulder


## Abstract
Abstract— Barrier certificates are real-valued functions used
to formally verify the safety of dynamical systems. For systems
with unknown dynamics, data-driven barrier certificates have
been developed to guarantee safety using only a finite set of
data. However, most existing methods rely on knowledge of
Lipschitz bound of the system and require a fine discretization
of the state set, leading to high sample complexity. In this paper,
we propose a novel data-driven framework for learning barrier
certificates for unknown monotone systems. Our approach is
based on a suitable embedding of barrier certificates into a
higher-dimensional space. By leveraging interval analysis, this
embedding enables us to establish data-driven safety certificates
for monotone systems. Unlike existing methods, our frame-
work is independent of Lipschitz continuity and quantization
parameters of the state set, allowing for arbitrary state-
space discretization and thereby alleviating extensive sampling
requirements. To efficiently construct barrier certificates, we
introduce suitable neural network architectures and train them
using an appropriately designed loss function. We illustrate
our approach through two case studies, demonstrating that our
method successfully finds separable embedded barrier certifi-
cates while substantially reducing sample complexity compared
to conventional neural barrier certificate methods, all while
maintaining formal correctness guarantees.



