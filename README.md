# COMSOL resources
Here is some useful information from COMSOL blogs, the multiphysics Cyclopedia, the Application Gallery and some forum answers. The only sensible source I know to learn about this software package.

## Basics about FEM in COMSOL
[Finite Element Method](https://www.comsol.com/multiphysics/finite-element-method) <br/>
[FEM Basics](https://www.comsol.com/blogs/solving-linear-static-finite-element-models) <br/>
[Weak form](https://www.comsol.de/blogs/strength-weak-form/) <br/>
[Weak form I](https://www.comsol.de/blogs/brief-introduction-weak-form/) <br/>
[Weak form II](https://www.comsol.de/blogs/implementing-the-weak-form-in-comsol-multiphysics/) <br/>
[Weak form III](https://www.comsol.de/blogs/discretizing-the-weak-form-equations/) <br/>
[Weak form IV](https://www.comsol.de/blogs/how-to-implement-the-weak-form-for-time-dependent-equations-2/) <br/>

## Solver issues
A science of itself - many models including nonlinearity and transient simulation do not converge with default settings.

[Solvers: Fully coupled or segregated approach](https://www.comsol.com/blogs/solving-multiphysics-problems) <br/>
[Direct and iterative solvers](https://www.comsol.com/blogs/solutions-linear-systems-equations-direct-iterative-solvers/) <br/>
[Time-dependent events](https://www.comsol.com/blogs/modeling-a-periodic-heat-load) <br/>
[Residual operator: Detect sources of convergence problems](https://www.comsol.com/blogs/plotting-the-algebraic-residual-to-study-model-convergence) <br/>

[Improving solver convergence](https://www.comsol.com/blogs/improving-convergence-multiphysics-problems) <br/>
[Solver convergence: Nonlinear stationary models](https://www.comsol.de/support/knowledgebase/103) <br/>

COMSOL solver for wave problems <br/>
[Manual setup of time step width](https://www.comsol.de/support/knowledgebase/1118) -> generalized alpha solver <br/>
[Scaling of variable fields](https://www.comsol.com/support/knowledgebase/1240) <br/>
[Smoothing of step loads to avoid high frequency solutions](https://www.comsol.com/support/knowledgebase/1244) <br/>

## Mechanics

### Some basics in mechanical simulation
[Different stress and strain measures](https://www.comsol.com/blogs/why-all-these-stresses-and-strains) <br/>
[Generalized plain strain modeling](https://www.comsol.de/blogs/how-to-model-generalized-plane-strain-with-comsol-multiphysics/) <br/>

[Stiffness of elastic structures 1D](http://www.comsol.com/blogs/computing-stiffness-linear-elastic-structures-part-1) <br/>
[Stiffness of elastic structures 2+3D](https://www.comsol.com/blogs/computing-stiffness-linear-elastic-structures-part-2) <br/>



### Reduction approaches
[Trusses, Plates etc. + coupling different parts, strcutural mechanics module](http://www.comsol.com/blogs/coupling-structural-mechanics-interfaces) <br/>
[Mech. lumped elements](https://www.comsol.de/blogs/how-to-use-lumped-elements-to-model-a-mechanical-system) <br/>
[Example: Lumped elements](https://www.comsol.de/blogs/examining-vibration-in-a-lumped-model-of-the-human-body) <br/>

<!--Initial strain and thermal stress
[1](http://www.comsol.com/blogs/structural-mechanics-tutorials-adding-initial-strain-and-thermal-stress) <br/> -->

### Damping
[Damping in Structural Dynamics: Theory and Sources](https://www.comsol.de/blogs/damping-in-structural-dynamics-theory-and-sources) <br/>
[Damping types in COMSOL](https://www.comsol.de/blogs/how-to-model-different-types-of-damping-in-comsol-multiphysics) <br/>
[Acoustic damping](https://www.comsol.com/blogs/modeling-acoustic-damping-processes) <br/>
[App: Viscoelastic damper](https://www.comsol.com/model/viscoelastic-structural-damper-4485) <br/>

[Forum](https://www.comsol.com/forum/thread/326/damping-problem-in-the-undamped-vibration-analysis-of-a-cantilevered-beam-in-com?last=2010-01-25T12:41:40Z)

### Shape memory
[SMA basics](https://www.comsol.de/blogs/the-elephants-of-materials-science-smas-never-forget-their-shape/) <br/>
[App: Uniaxial loading](https://www.comsol.de/model/uniaxial-loading-of-shape-memory-alloy-54871) <br/>


### Elastoplasticity
[Fatigue and failure](https://www.comsol.com/blogs/modeling-fatigue-failure-in-elastoplastic-materials) <br/>
[Example: elastoplasticity](https://www.comsol.com/blogs/how-to-implement-elastoplasticity-in-a-model-using-external-materials) <br/>

### User defined materials
[External material model](https://www.comsol.com/blogs/accessing-external-material-models-for-structural-mechanics/) <br/>
[Example: elastoplasticity](https://www.comsol.com/blogs/how-to-implement-elastoplasticity-in-a-model-using-external-materials/) <br/>
[Forum](https://www.comsol.co.in/support/knowledgebase/1281) <br/>
[App: Damage model](https://www.comsol.com/model/external-material-examples-structural-mechanics-32331) <br/>
