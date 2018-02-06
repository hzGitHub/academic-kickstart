+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "Efficient algorithms for Multi-physics multi-scale modeling"

# Project summary to display on homepage.
summary = "Large scale multiphysics modeling of coupled problems of electrosurgery in real time."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "mpms.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["coupled"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++

Developing an interactive simulation environment for electrosurgery that includes coupled electro-thermo-mechanical multiphysics modeling, continuum level, micromechanical level multilevel modeling and topological change can be challenging. Current best practices for the efficient solution of such problem are based almost exclusively on multigrid methods and preconditioned Krylov subspace methods. Design of efficient application specific monolithic multiphysics multigrid solvers or preconditioners is challenging. Therefore, our aim in this project is to develop efficient finite element solver and block preconditioning technique that can effectively deflate the spectrum of the system matrix leading to exponential convergence of the Arnoldi iterations for the multiphysics, multilevel modeling of electrosurgery without compromising physical fidelity and stability. Research efforts are focused on:
##### Deflation based block preconditioner for efficient solution of electrosurgical simulation
##### Reduced order modeling of large scale electrosurgical simulation
{{< figure src="/img/mps.jpg" title="Contour plots for 50 W power setting with a fixed active electrode" >}}