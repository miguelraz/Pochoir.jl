# Pochoir

This is an early stages implementation of [Pochoir](https://github.com/Pochoir/Pochoir), the stencil compiler.

[The paper it is based on is here](http://supertech.csail.mit.edu/papers/pochoir_spaa11.pdf)

# Roadmap
- [ ] Write the spec
- [ ] 2D Heat equation test case
- [ ] Trapezoidal cuts
- [ ] Implement the parser
- [ ] Cache-oblivious parallel algo
- [ ] Pass the test cases from the paper

| Benchmark     | Dims | Serial time | Parallel | Speedup |
|---------------|------|-------------|----------|---------|
| Heat equation |      |             |          |         |
| Wave equation |      |             |          |         |
| Life          |      |             |          |         |
| LBM           |      |             |          |         |
| RNA           |      |             |          |         |
| PSA           |      |             |          |         |
| LCS           |      |             |          |         |
| APOP          |      |             |          |         |

- [ ] Optimize the daylights out of it

| Optimization (Section 4)               | Implemented |
|----------------------------------------|-------------|
| Code cloning                           |             |
| loop index calculations                |             |
| unifying periodic and non-peridoic BCs |             |
| coarsening the base case of recursion  |             |

