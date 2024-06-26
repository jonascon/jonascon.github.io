---
title: "Explicit Symplectic Integrators for Non-Separable Hamiltonians in Molecular Dynamics"
collection: publications
permalink: /publication/bachelorsthesis
excerpt: "Bachelor's thesis in computational physics at KTH."
date: 2019-06-01
venue: "KTH Royal Institute of Technology, Bachelor's thesis, 2019"
paperurl: 'http://jonascon.github.io/files/FULLTEXT01.pdf'

---
In molecular dynamics, mathematical models of metallic systems should in general have
the temperature of the system as a dependent variable [1]. In particular, the potential
energy term of the Hamiltonian function of the interaction model should be dependent on
temperature in addition to interparticular distances. This puts the Hamiltonian function
on a form which is generally non-separable. Conventional explicit numerical methods
which are symplectic when used to integrate the equations of motion of systems with
separable Hamiltonians are not in general symplectic when used to integrate the equations
of motion of systems with a non-separable Hamiltonian. Hence, an integrator which
sustains symplecticity when used in a system with non-separable Hamiltonian is sought.
A family of explicit integrators which are symplectic when integrating systems with
a non-separable Hamiltonian are shown to exhibit similar or superior performance to
the Velocity Verlet and fourth-order Runge-Kutta schemes, albeit with the drawback
of numerical instability when used on a system where forces depend exponentially on
the inverted interparticular distances. To the knowledge of the authors, this study is
the first time this family of integrators is applied in the context of molecular dynamics.
The results of this study provide a first indication that a comprehensive solution to
the problem of integrating the equations of motion of a system with a non-separable
Hamiltonian explicitly and symplectically is not provided by the considered family of
integrators. However, further investigations into using this family of integrators in other
molecular dynamics systems than those investigated here are needed to provide a more
definitive conclusion.

[Download paper here](http://jonascon.github.io/files/FULLTEXT01.pdf)
