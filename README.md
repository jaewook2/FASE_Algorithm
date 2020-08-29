# FASE_Algorithm

Conventional service function chaining (SFC) poses requirements of additional processing time of service functions (SFs) and increased routing time owing to detoured paths. To solve these problems, approaches for the implementation of SFC in PDP switch that can satisfy the requested SF processing orders have been studied, which can be categorized into: 1) a redundant SF approach and 2) re-circulation approach. However, the redundant SF and re-circulation approaches have contrasting advantages and disadvantages.  Thus, we attempt to find the optimal SF embedding strategy that minimizes the SFC completion time while utilizing the PDP switch resource efficiently by achieving a balance between these approaches. A flow-aware SF embedding (FASE) algorithm that complementary combines the redundant SF and re-circulation approaches is devised to solve the formulated optimization problem with low-complexity. FASE is implemented over a commercial PDP switch and experimental results demonstrate that FASE can reduce the SFC completion time compared with conventional approaches while utilizing the given switch resources efficiently.

The detailed optimization problem and FASE algorithm are written in ' The optimization problem and FASE algorithm.pdf' document. Also, the implemented codes of FASE and its test conde on the PDP switch (i.e., bmv2 and Tofino switch) can be found at FASE folder and DataPlane folder, respectively.
