PIQP supports dense and sparse problem formulations. For small and dense problems the dense interface is preferred since vectorized instructions and cache locality can be exploited more efficiently, but for sparse problems the sparse interface and result in significant speedups.