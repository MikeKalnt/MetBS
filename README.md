  # Official implementation: "Adaptive Resource Allocation for Virtualized Base Stations in O-RAN with Online Learning"

This code sample includes the implementation of our algorithm, MetBS, which is used for scheduling virtualized Base Stations (vBS) in Open-Radio Access Networks (O-RAN).

Paper: https://doi.org/10.1109/TCOMM.2024.3461569

## Abstract

> Open RAN systems, with their virtualized base stations (vBSs), offer increased flexibility and reduced costs, vendor diversity, and interoperability. However, optimizing the allocation of radio resources in such systems raises new challenges due to the volatile vBSs operation, and the dynamic network conditions and user demands they are called to support. Leveraging the novel O-RAN multi-tier control architecture, we propose a new set of resource allocation threshold policies with the aim of balancing the vBSs’ performance and energy consumption in a robust and provably optimal fashion. To that end, we introduce an online learning algorithm that operates under minimal assumptions and without requiring knowledge of the environment, hence being suitable even for “challenging” environments with non-stationary or adversarial demands and conditions. We also develop a meta-learning scheme that utilizes other available algorithmic schemes, e.g., tailored for more “easy” environments, by choosing dynamically the best-performing algorithm; thus enhancing the system’s effectiveness. We prove that the proposed solutions achieve sub-linear regret (zero optimality gap), and characterize their dependence on the main system parameters. The performance of the algorithms is evaluated with real-world data from a testbed, in stationary and adversarial conditions, indicating energy savings of up to 64.5% compared with several state-of-the-art benchmarks.

## Citing Work

To acknowledge the use of the source code, please use the following reference:

### Plain Text

M. Kalntis, G. Iosifidis and F. A. Kuipers, "Adaptive Resource Allocation for Virtualized Base Stations in O-RAN with Online Learning," in IEEE Transactions on Communications, doi: 10.1109/TCOMM.2024.3461569.

### BibTeX

```
@article{kalntis_tcom24,
  author={Kalntis, Michail and Iosifidis, George and Kuipers, Fernando A.},
  journal={IEEE Transactions on Communications}, 
  title={Adaptive Resource Allocation for Virtualized Base Stations in O-RAN with Online Learning}, 
  year={2024},
  volume={},
  number={},
  pages={1-1},
  doi={10.1109/TCOMM.2024.3461569}}
```

