

## Abstract

A hybrid intelligent optimization method by improving particle swarm optimization and genetic algorithm (PSO-GA) is proposed for solving multi-objective optimal control problem (MOOCP) governed by ordinary differential equations (ODEs) in nonlinear systems. This method combines the global search capability of heuristic algorithm and the rapid convergence of deterministic algorithm to generate approximately uniform Pareto front. Firstly, the MOOCP is converted into a single-objective optimal control problem (SOOCP) subject to inequality point constraints using an adaptive 𝜀-constraint method. Secondly, the enhanced PSO is combined with a two-criteria GA to locate the global optimal region of SOOCP. Thirdly, sequential quadratic programming (SQP) algorithm is applied in the global optimal region to achieve fast convergence to high local accuracy solutions satisfying optimality conditions. Finally, the effectiveness and superiority of the proposed method are ultimately validated through numerical simulations and comparative analyses against state-of-the-art algorithms. Specifically, the hybrid intelligent optimization algorithm shows a 7.65% improvement in hypervolume and a 46.60% reduction in spacing metric compared to the suboptimal algorithm.

## Citation

If you found this work useful or interesting for your own research, we would appreciate if you could cite our work.


```bibtex
@article{du2025hybrid,
  title={Hybrid intelligent multi-objective optimal control of ODE-constrained nonlinear systems},
  author={Du, Linqing and Fu, Jun and Li, Huan},
  journal={Journal of the Franklin Institute},
  pages={108378},
  year={2025},
  publisher={Elsevier}
}
```

*Feel free to leave any questions in the issues of Github or email the author at (lqingdu@163.com).*
