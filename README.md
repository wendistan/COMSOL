# COMSOL resources
Here is some useful information from COMSOL blogs, the multiphysics Cyclopedia, the Application Gallery and some forum answers. The only sensible source I know to learn about this software package. For completeness, here is the official documentation:
[COMSOL documentation](https://doc.comsol.com/)

## Learning
[Learning Center](https://www.comsol.de/c/etux) </br>
[Multiphysics Cyclopedia](https://www.comsol.com/multiphysics) </br>

## COMSOL handling
[How to Navigate the COMSOL Multiphysics® User Interface](https://www.comsol.com/support/learning-center/article/34991/12) <br/>
[Reduce COMSOL file size](https://www.comsol.com/support/knowledgebase/1238) <br/>
[Performing a Mesh Refinement Study](https://www.comsol.com/support/knowledgebase/1261) <br/>
[Controlling the Time Dependent Solver Timesteps](https://www.comsol.com/support/knowledgebase/1254) <br/>

## Basics about FEM in COMSOL
[Finite Element Method](https://www.comsol.com/multiphysics/finite-element-method) <br/>
[Finite Element Analysis (FEA) Software](https://www.comsol.com/multiphysics/fea-software) <br/>
[FEM Basics](https://www.comsol.com/blogs/solving-linear-static-finite-element-models) <br/>
[The Strength of the Weak Form](https://www.comsol.de/blogs/strength-weak-form/) <br/>
[Weak form I](https://www.comsol.de/blogs/brief-introduction-weak-form/) <br/>
[Weak form II](https://www.comsol.de/blogs/implementing-the-weak-form-in-comsol-multiphysics/) <br/>
[Weak form III](https://www.comsol.de/blogs/discretizing-the-weak-form-equations/) <br/>
[Weak form IV](https://www.comsol.de/blogs/how-to-implement-the-weak-form-for-time-dependent-equations-2/) <br/>

[Solving Linear Static Finite Element Models](https://www.comsol.com/blogs/solving-linear-static-finite-element-models) <br/>
[Solving Nonlinear Static Finite Element Problems](https://www.comsol.com/blogs/solving-nonlinear-static-finite-element-problems) <br/>

## Solver issues
A science of itself - many models including nonlinearity and transient simulation do not converge with default settings.

[Solvers: Fully coupled or segregated approach](https://www.comsol.com/blogs/solving-multiphysics-problems) <br/>
[Direct and iterative solvers](https://www.comsol.com/blogs/solutions-linear-systems-equations-direct-iterative-solvers/) <br/>
[Time-dependent events](https://www.comsol.com/blogs/modeling-a-periodic-heat-load) <br/>
[Residual operator: Detect sources of convergence problems](https://www.comsol.com/blogs/plotting-the-algebraic-residual-to-study-model-convergence) <br/>

[Improving solver convergence](https://www.comsol.com/blogs/improving-convergence-multiphysics-problems) <br/>
[Solver convergence: Nonlinear stationary models](https://www.comsol.de/support/knowledgebase/103) <br/>
[Improving convergence in nonlinear time dependent models](https://www.comsol.de/support/knowledgebase/1127) <br/>

COMSOL solver for wave problems <br/>
[Manual setup of time step width](https://www.comsol.de/support/knowledgebase/1118) -> generalized alpha solver <br/>
[Scaling of variable fields](https://www.comsol.com/support/knowledgebase/1240) <br/>
[Smoothing of step loads to avoid high frequency solutions](https://www.comsol.com/support/knowledgebase/1244) <br/>

## Special boundary conditions (BCs)
the following links shows how to realize a moving heat spot as BC <br/>
[Conditional BCs](https://www.comsol.com/blogs/how-to-make-boundary-conditions-conditional-in-your-simulation) <br/>
[Example: Beam with a Traveling Load](https://www.comsol.com/model/beam-with-a-traveling-load-20401) <br/>

## Variational problems
[Modeling Soap Films and Other Variational Problems](https://www.comsol.com/blogs/introduction-to-modeling-soap-films-and-other-variational-problems) <br/>
[BCs and Constraints](https://www.comsol.com/blogs/specifying-boundary-conditions-and-constraints-in-variational-problems) <br/>
[Constraint enforcement](https://www.comsol.de/blogs/methods-for-dealing-with-numerical-issues-in-constraint-enforcement) <br/>

## Equation-based modeling
[Equation based modeling](https://www.comsol.de/blogs/3-examples-of-equation-based-modeling-in-comsol-multiphysics) <br/>





## Mechanics

### Some basics in mechanical simulation
[Basics in linear elasticity](https://www.comsol.com/blogs/modeling-linear-elastic-materials-how-difficult-can-it-be) see also links at the end! <br/>
[Geometric nonlinearity](https://www.comsol.com/blogs/what-is-geometric-nonlinearity) <br/>


[Different stress and strain measures](https://www.comsol.com/blogs/why-all-these-stresses-and-strains) <br/>
[Generalized plain strain modeling](https://www.comsol.de/blogs/how-to-model-generalized-plane-strain-with-comsol-multiphysics/) <br/>
[What Is the Difference Between Plane Stress and Plane Strain?](https://www.comsol.com/blogs/what-is-the-difference-between-plane-stress-and-plane-strain) <br/>

[Stiffness of elastic structures 1D](http://www.comsol.com/blogs/computing-stiffness-linear-elastic-structures-part-1) <br/>
[Stiffness of elastic structures 2+3D](https://www.comsol.com/blogs/computing-stiffness-linear-elastic-structures-part-2) <br/>

[Mechanical multi/instability](https://www.comsol.de/blogs/can-a-stiffness-be-negative/) links to Applications <br/>


### Large deformation
App: [Large Deformation Analysis of a Beam](https://www.comsol.com/model/large-deformation-analysis-of-a-beam-204) <br/>
App: [Spherical Cap with Central Point Load](https://www.comsol.de/model/spherical-cap-with-central-point-load-67161) <br/>


### Reduction approaches
[Trusses, Plates etc. + coupling different parts, strcutural mechanics module](http://www.comsol.com/blogs/coupling-structural-mechanics-interfaces) <br/>
[Mech. lumped elements](https://www.comsol.de/blogs/how-to-use-lumped-elements-to-model-a-mechanical-system) <br/>
[Example: Lumped elements](https://www.comsol.de/blogs/examining-vibration-in-a-lumped-model-of-the-human-body) <br/>

<!--Initial strain and thermal stress
[1](http://www.comsol.com/blogs/structural-mechanics-tutorials-adding-initial-strain-and-thermal-stress) <br/> -->

[App: Rigid bodies](https://www.comsol.com/model/modeling-rigid-bodies-10566) <br/>


### Damping
[Damping in Structural Dynamics: Theory and Sources](https://www.comsol.de/blogs/damping-in-structural-dynamics-theory-and-sources) <br/>
[Damping types in COMSOL](https://www.comsol.de/blogs/how-to-model-different-types-of-damping-in-comsol-multiphysics) <br/>
[Acoustic damping](https://www.comsol.com/blogs/modeling-acoustic-damping-processes) <br/>
[App: Viscoelastic damper](https://www.comsol.com/model/viscoelastic-structural-damper-4485) <br/>

[Forum](https://www.comsol.com/forum/thread/326/damping-problem-in-the-undamped-vibration-analysis-of-a-cantilevered-beam-in-com?last=2010-01-25T12:41:40Z)

### Shape memory
[SMA basics](https://www.comsol.de/blogs/the-elephants-of-materials-science-smas-never-forget-their-shape/) <br/>
[App: Uniaxial loading](https://www.comsol.de/model/uniaxial-loading-of-shape-memory-alloy-54871) <br/>
[App: Stent](https://www.comsol.de/model/shape-memory-alloy-self-expanding-stent-65851) <br/>

### Nonlinearity and Elastoplasticity
[Introducing Nonlinear Elastic Materials](https://www.comsol.com/blogs/introducing-nonlinear-elastic-materials) links! <br/>

[Fatigue and failure](https://www.comsol.com/blogs/modeling-fatigue-failure-in-elastoplastic-materials) <br/>
[Example: elastoplasticity](https://www.comsol.com/blogs/how-to-implement-elastoplasticity-in-a-model-using-external-materials) <br/>


### Thermomechanics
[Modeling Thermomechanical Fatigue in COMSOL Multiphysics®](https://www.comsol.com/blogs/modeling-thermomechanical-fatigue-in-comsol-multiphysics)


### Contact mechanics, adhesion, thermal transfer
[How to Model Adhesion and Decohesion in COMSOL Multiphysics](https://www.comsol.de/blogs/how-to-model-adhesion-and-decohesion-in-comsol-multiphysics/) <br/>
[Thermal Connection, Facing Boundary](https://www.comsol.com/model/thermal-connection-facing-boundary-110951)<br/>
[Analyzing Electrical and Thermal Conductance in a Contact Switch](https://www.comsol.de/blogs/analyzing-electrical-thermal-conductance-contact-switch/)


### Fatigue and fracture
[Material Fatigue](https://www.comsol.com/multiphysics/material-fatigue) <br/>

### User defined materials
[External material model](https://www.comsol.com/blogs/accessing-external-material-models-for-structural-mechanics/) &nbsp;&nbsp; [issue1](https://www.comsol.de/support/knowledgebase/1281) <br/>
[App: External Material Examples, Structural Mechanics](https://www.comsol.de/model/external-material-examples-structural-mechanics-32331) <br/>
[Example: elastoplasticity](https://www.comsol.com/blogs/how-to-implement-elastoplasticity-in-a-model-using-external-materials/) <br/>
[App: Damage model](https://www.comsol.com/model/external-material-examples-structural-mechanics-32331) <br/>

[Define material properties with functions](https://www.comsol.com/video/use-functions-define-material-property) <br/>


### Bone modeling
[Generating a Simulation Mesh of a Femur From 3D Data](https://www.comsol.com/blogs/generating-a-simulation-mesh-of-a-femur-from-3d-data) <br/>
[Modeling Bone Strength Using Isotropic and Anisotropic Materials](https://www.comsol.com/blogs/modeling-bone-strength-using-isotropic-anisotropic-materials/) <br/>
[Bone Remodeling Following Total Hip Replacement](https://www.comsol.com/paper/bone-remodeling-following-total-hip-replacement-short-stem-versus-long-stem-impl-13857) <br/>
[Design and Strain Analysis of Artificial Femoral Head and Stem](https://www.comsol.com/paper/design-and-strain-analysis-of-artificial-femoral-head-and-stem-19437) <br/>
[On the Influence of Cancellous Bone Structure upon the Electric Field Distribution of Electrostimulative Implants](https://www.comsol.com/paper/on-the-influence-of-cancellous-bone-structure-upon-the-electric-field-distributi-18231) <br/>
[Modeling of Articular Cartilage Growth Using COMSOL](https://www.comsol.com/paper/modeling-of-articular-cartilage-growth-using-comsol-12094) <br/>


## Magnetism

[Quick Intro to Permanent Magnet Modeling](https://www.comsol.com/blogs/quick-intro-permanent-magnet-modeling/)  Also check [App](https://www.comsol.com/model/permanent-magnet-78) <br/>
[Modeling Ferromagnetic Materials in COMSOL Multiphysics](https://www.comsol.de/blogs/modeling-ferromagnetic-materials-in-comsol-multiphysics/) <br/>
[Magnetostatics, Theory](https://www.comsol.com/multiphysics/magnetostatics-theory)


## Phase-field

[Localized Corrosion Using the Phase Field Method](https://www.comsol.com/model/localized-corrosion-using-the-phase-field-method-79851) <br/>



## Testing and design
[Product design and testing](https://www.comsol.de/blogs/veryst-combines-material-testing-and-simulation-for-reliable-results) <br/>
[Obtaining Material Data for Structural Mechanics from Measurements, part 1](https://www.comsol.com/blogs/obtaining-material-data-for-structural-mechanics-from-measurements) <br/>
[Obtaining Material Data for Structural Mechanics from Measurements, part 2](https://www.comsol.com/blogs/part-2-obtaining-material-data-for-structural-mechanics-from-measurements) <br/>
[App: Parameter Estimation for a Tensile Test](https://www.comsol.de/model/parameter-estimation-for-a-tensile-test-88761) <br/>


## Meshing and creating input geometries
[Editing and Repairing Imported Meshes in COMSOL Multiphysics®](https://www.comsol.com/blogs/editing-and-repairing-imported-meshes-in-comsol-multiphysics)
[How to Convert Point Cloud Data to Surfaces and Solids](https://www.comsol.com/blogs/how-to-convert-point-cloud-data-to-surfaces-and-solids)
