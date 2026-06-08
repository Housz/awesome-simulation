# Awesome Physics-Based Simulation / Animation

A curated list of courses, researchers, literature, code, and other resources for physics-based simulation and animation. Continuously updated, contributions are welcome!

[GitHub: github.com/Housz/awesome-simulation](https://github.com/Housz/awesome-simulation) 

## 1 Courses

**Computer Graphics Fundamentals:**

- [Lingqi Yan] [GAMES101: Introduction to Modern Computer Graphics](https://sites.cs.ucsb.edu/~lingqi/teaching/games101.html) *(in Chinese)*
- [Ligang Liu] [2020 USTC "Computer Graphics" Undergraduate Course](https://www.bilibili.com/video/BV1iT4y1o7oM) *(in Chinese)*
- [OpenGL] [LearnOpenGL](https://learnopengl.com/) (Also available in [Chinese](https://learnopengl-cn.github.io/)) The best introductory tutorial for OpenGL.

**Physics Simulation:**

- [Huamin Wang] [GAMES103: Introduction to Physics-Based Computer Animation](http://games-cn.org/games103/) *(in Chinese)* Covers math background, rigid bodies, mass-spring systems, constraints, collisions, soft bodies, FEM, and fluids. Very beginner-friendly. The four assignments (rigid body, cloth, soft body, fluid) use the Unity engine.
- [Yuanming Hu] [GAMES201: Advanced Physics Engines 2020](http://games-cn.org/games201/) *(in Chinese)* High depth and breadth; challenging without a numerical computation background. Covers Lagrangian, Eulerian, hybrid Eulerian-Lagrangian views, and high-performance physics engines.
- [Tiantian Liu] [Taichi Graphics Course](https://space.bilibili.com/1779922645?from=search&seid=3236551890279933972&spm_id_from=333.337.0.0) *(in Chinese)* A CG course using the Taichi programming language. Covers Taichi data structures, ray tracing, elastomers (FEM, time integration), and fluids.
- [Xiaowei He] [GAMES401: PeriDyno Physics Simulation Programming and Practice (Updating)](https://www.bilibili.com/video/BV15M4y1U76M/) *(in Chinese)* Based on the PeriDyno engine. Covers GPU programming (CUDA), rigid body dynamics, SPH, peridynamics, and Vulkan basics.
- [Minchen Li] [Physics-based Animation of Solids and Fluids](http://www.cs.cmu.edu/~15769-f23/) CMU physics simulation seminar. Covers optimization-based time integration, mass-spring systems, FEM, IPC, cloth, rigid bodies, reduced-order simulation, and fluids (Lagrangian, PIC/FLIP, MPM).
- [Teacher Xiaopeng] [High-Performance Parallel Programming and Optimization Series](https://www.bilibili.com/video/BV1fa411r7zp/) *(in Chinese)* Covers CMake, modern C++, compiler optimization, TBB, memory access optimization, CUDA, and modern OpenGL.
- [Xi Wang] [GAMES104: Modern Game Engines](https://www.bilibili.com/video/BV1oU4y1R7Km) *(in Chinese)* Lectures 10/11 cover physics systems in game engines; Lectures 8/9 cover animation techniques.
- [Ladislav Kavan] [CIS563 Physics based Animation (2014)](https://www.youtube.com/watch?v=Q0D3tUViO6Y&list=PL_a9tY9IhJuM2dIVCH_ZC0Pn5871eDY7_&ab_channel=LadislavKavan) Very detailed mathematical derivations. Covers mass-spring, PBD, Shape Matching, PDE basics, FEM, Projective Dynamics, rigid bodies, etc. [CIS563 (2015)](https://www.youtube.com/watch?v=Zw81lwV65wk) adds fluids. [Supplementary content by Tiantian Liu](https://www.youtube.com/user/ltt1598/videos) *(in Chinese)*. [CS6660 (2017)](https://www.youtube.com/watch?v=sSKyQIxdhdA) adds Lagrangian/Hamiltonian mechanics perspectives.
- [Eitan Grinspun] [Animation and CGI Motion](https://learning.edx.org/course/course-v1:ColumbiaX+CSMM.104x+1T2017/home) Highly beginner-friendly, detailed derivations. Covers ODE numerical integration, Lagrangian mechanics, collisions/contact, continuum mechanics, FEM, shells/cloth, fluids, etc.
- [Matthias Müller] [Ten Minute Physics](https://matthias-research.github.io/pages/tenMinutePhysics/index.html) Features JavaScript implementations for easy hands-on practice. Covers PBD/XPBD, soft bodies, spatial hashing, cloth, GPU programming basics, Eulerian/hybrid fluids, etc.
- [Adam Bargteil] [SIGGRAPH'19 Course: An Introduction to Physics-Based Animation](https://www.youtube.com/watch?v=b_WJ-HwalwU) Introduces basic concepts of physics simulation with accompanying notes.
- [David I.W. Levin] [CSC417/CSC2549 Physics-Based Animation](https://github.com/dilevin/CSC417-physics-based-animation) | [YouTube](https://www.youtube.com/channel/UCIM0HrQVDcUYdrZvSwuUJgA/videos) | [Bilibili](https://www.bilibili.com/video/BV1GB4y1u72S) Covers Lagrangian mechanics, mass-spring systems, FEM, rigid bodies, and fluids.
- [Doug L. James] [CS 5643: Physically Based Animation for Computer Graphics (2015)](https://www.cs.cornell.edu/courses/cs5643/2015sp/) A comprehensive course that lists classic papers for each topic. Other courses: [CS 448Z (2021)](http://graphics.stanford.edu/courses/cs448z/), [CS 248 (2022)](https://gfxcourses.stanford.edu/cs248/winter22), [CS 348C (2022)](http://graphics.stanford.edu/courses/cs348c/).
- [Jernej Barbič] [CSCI 520 Computer Animation and Simulation](https://viterbi-web.usc.edu/~jbarbic/cs520-s22/)
- [Jan Bender] [Physics Simulation in Visual Computing](https://interactivecomputergraphics.github.io/physics-simulation/)

**Math & Numerical Foundations:**

- **Matrix Computation:** [GAMES103 Math Basics](http://games-cn.org/games103/) *(in Chinese)*, [3Blue1Brown - Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab), [Matrix Calculus Tutorial](https://zhuanlan.zhihu.com/p/24709748) *(in Chinese)*, [Numerical Recipes](http://numerical.recipes/book/book.html), [Wiki: Matrix calculus](https://en.m.wikipedia.org/wiki/Matrix_calculus).
- **Basic Numerical Analysis:** [Numerical Analysis 2020 Spring](https://www.bilibili.com/video/BV18741177td) by Yanan Zhang, Soochow University *(in Chinese)*. 
- **Advanced Numerical Analysis:** [Numerical Analysis USTC](https://www.bilibili.com/video/BV1T4411D7x5) by Chi-Wang Shu, Brown University. An excellent numerical analysis course *(in Chinese)*.
- **Basic Optimization:** [Optimization Theory and Methods](https://space.bilibili.com/507629580) by Xueting Cui, SUFE *(in Chinese)*. Reference texts include Stephen Boyd's *Convex Optimization* and Jorge Nocedal's *Numerical Optimization*.
- **Advanced Optimization:** [Boyd's Stanford Course (Bilibili Mirror)](https://www.bilibili.com/video/BV1Pg4y187Ed) Taught by Stephen Boyd.
- **Scientific Computing:** [EAS205 Applications of Scientific Computation (2014)](https://www.youtube.com/watch?v=Ikl1wnwIOmM&list=PL_a9tY9IhJuPDEDq97tq0uKXpsTZYBIXe&ab_channel=LadislavKavan) by Ladislav Kavan. Covers vector/matrix math, linear systems, group theory, SVD, etc.
- **Books:** *Numerical Recipes*, *Matrix Computations*, *Scientific Computing: An Introductory Survey*, *Iterative methods for sparse linear systems*, *A multigrid tutorial*.

## 2 Researchers & Teams

**Researchers:**
- [Yuanming Hu](https://yuanming.taichi.graphics/) (MIT, Taichi Graphics) | [Zhihu](https://www.zhihu.com/people/19787805e0d1f80fe5501ec60be84d6a) *(in Chinese)* | [Frozen in 99 lines of code](https://zhuanlan.zhihu.com/p/97700605) *(in Chinese)*
- [Ligang Liu](http://staff.ustc.edu.cn/~lgliu/) (USTC)
- [Tiantian Liu](https://tiantianliu.cn/) (UPenn, Taichi Graphics) | [Zhihu](https://www.zhihu.com/people/b71d9a706d0216654be0f16cfd0b2b5a) *(in Chinese)*
- [Huamin Wang](https://web.cse.ohio-state.edu/~wang.3602/index.html) (Ohio State University, Style3D) | [Zhihu](https://www.zhihu.com/people/ca6e5cf45df33e1ca946aab6a5295ad2) *(in Chinese)*
- [Chenfanfu Jiang](https://www.math.ucla.edu/~cffjiang/) (UCLA) | [Zhihu](https://www.zhihu.com/people/346d9a6d4914ba9d4f1fcf7b4e41e514) *(in Chinese)*
- [Xinxin Zhang](https://zhxx1987.github.io/) (UBC, ZENO) | [Zhihu](https://www.zhihu.com/people/9d0cd62f9071c2b003b2ef7b017fb7f5) *(in Chinese)*
- [Minchen Li](https://www.cs.cmu.edu/~minchenl/) (CMU) | [Zhihu](https://www.zhihu.com/people/9f3ee58deeb19551bd92d9591e4503d7) *(in Chinese)*
- [Yun (Raymond) Fei](http://yunfei.work/) (Adobe) | [Zhihu](https://www.zhihu.com/people/ecf74d1b95762c56eebfe55935655e26) *(in Chinese)*
- [Bo Ren](http://ren-bo.net/) (Nankai University)
- [Jin Huang](http://www.cad.zju.edu.cn/home/hj/index.xml) (Zhejiang University)
- [Min Tang](https://min-tang.github.io/home/Data/contact-ch.html) (Zhejiang University)
- [Ming Gao](https://mingg13.github.io/) (miHoYo)
- [Bo Zhu](https://faculty.cc.gatech.edu/~bozhu/) (GaTech)
- [Xiaowei He](http://peridynamics.com/index.html) (CAS)
- [Libin Liu](http://libliu.info/) (Peking University), Creator of [GAMES105: Computer Character Animation](https://games-105.github.io/) *(in Chinese)*
- [Xiaopei Liu](https://faculty.sist.shanghaitech.edu.cn/faculty/liuxp/index_ch.htm) (ShanghaiTech University)
- [Yifei Li](https://people.csail.mit.edu/liyifei/) (MIT)
- [David Baraff](http://www.cs.cmu.edu/~baraff/) & [Andrew Witkin](https://www.cs.cmu.edu/afs/cs.cmu.edu/user/aw/www/index.html) (CMU, Pixar) — Pioneers of the field.
- [Demetri Terzopoulos](http://web.cs.ucla.edu/~dt/) (UCLA)
- [Eitan Grinspun](https://www.dgp.toronto.edu/~eitan/) (University of Toronto) Geometry, physics, etc.
- [Ladislav Kavan](https://www.cs.utah.edu/~ladislav/) (University of Utah, Facebook) Soft bodies, numerical methods.
- [Robert Bridson](https://www.cs.ubc.ca/~rbridson/) (UBC, Autodesk) Fluids. Author of *Fluid Simulation for Computer Graphics*.
- [Joseph Teran](https://math.ucdavis.edu/~jteran/) (UC Davis)
- [Markus Gross](https://cgl.ethz.ch/people/grossm/) (ETH Zurich)
- [Jos Stam](https://www.josstam.com/) (Nvidia) Inventor of Semi-Lagrangian advection in CG. Author of *The Art of Fluid Animation*.
- [Jan Bender](https://animation.rwth-aachen.de/person/1/) (RWTH Aachen University) SPH, soft bodies.
- [Matthias Müller](https://matthias-research.github.io/pages/) & [Miles Macklin](http://blog.mmacklin.com/) (NVIDIA) Creators of PBD/XPBD.
- [Dinesh K. Pai](https://sensorimotor.cs.ubc.ca/pai/) (UBC)
- [Paul G. Kry](https://www.cs.mcgill.ca/~kry/) (McGill) & [Sheldon Andrews](http://profs.etsmtl.ca/sandrews/) (ÉTS) Rigid bodies, contact & friction.
- [Jernej Barbic](https://viterbi-web.usc.edu/~jbarbic/) (USC)
- [David I.W. Levin](http://142.93.146.228/researchdb/#aboutme) (University of Toronto)
- [Doug L. James](http://graphics.stanford.edu/~djames/) (Stanford)
- [Theodore Kim](https://www.tkim.graphics/) (Yale)
- [Matthias Teschner](https://cg.informatik.uni-freiburg.de/teschner.htm) (University of Freiburg)
- [Eftychios Sifakis](https://pages.cs.wisc.edu/~sifakis/) (UW-Madison)
- [Kenny Erleben](https://iphys.wordpress.com/) (University of Copenhagen) Author of [Physics-Based Animation](https://iphys.wordpress.com/2020/01/12/free-textbook-physics-based-animation/).
- [Jeff Trinkle](https://engineering.lehigh.edu/faculty/jeffrey-c-trinkle) (Lehigh University) Rigid bodies, robotics.
- [Doyub Kim](https://doyub.com/) Author of *Fluid Engine Development*.
- [Roy Featherstone](http://royfeatherstone.org/) (Italian Institute of Technology) Rigid bodies, robotics.
- [C. Karen Liu](https://ckllab.stanford.edu/) (Stanford) Robotics, RL.
- [Xue Bin (Jason) Peng](https://xbpeng.github.io/) (Simon Fraser University) Robotics, RL.
- [Shinjiro Sueda](https://people.engr.tamu.edu/sueda/index.html) (Texas A&M) Robotics, elastomers.
- [Physics Simulation Genealogy Tree](https://naotu.baidu.com/file/eb1a5ebf45eac4eb4c783aae20bf662e?token=6333ba7d098d633c) compiled by Yu Peng *(in Chinese)*.

*(To be continued...)*

**Research Teams**
- [Stanford Computer Graphics Laboratory](https://graphics.stanford.edu/)
- [Dynamic Graphics Project](https://www.dgp.toronto.edu/) (University of Toronto)
- [Computer Graphics UC Berkeley](http://graphics.berkeley.edu/)
- [Computational Sciences Group](http://www.computationalsciences.org/) (KAUST)
- [Carnegie Mellon Graphics Lab](http://graphics.cs.cmu.edu/)
- [Pixar Research](https://graphics.pixar.com/)

## 3 Resource Collections

- **[GAMES: Graphics And Mixed Environment Seminar](http://games-cn.org/)** Chinese CG communication platform *(in Chinese)*.
- **[USTC "Frontiers of Computer Graphics" Summer School](http://staff.ustc.edu.cn/~lgliu/Courses/SummerSchool/USTC-summer-school.html)** | [Bilibili Videos](https://space.bilibili.com/1598639097) *(in Chinese)*.
- **[Physics-Based Animation (physicsbasedanimation.com)](http://www.physicsbasedanimation.com/)** Paper collection.
- **[Resource for Computer Graphics (Ke-Sen Huang)](http://kesen.realtimerendering.com/)** Paper collection.
- **[SIGGRAPH Courses & Resources](https://blog.selfshadow.com/)**
- **[Computer Graphics and Simulation Research Results](https://iphys.wordpress.com/)**
- **[Interactive Graphics (SPH, PBD, etc.)](https://interactive-graphics.de/)** Code and papers.
- **[GraphiCon Zhihu Column](https://zhuanlan.zhihu.com/graphicon)** *(in Chinese)*.

*(To be continued...)*

## 4 Introductory Literature

- **[Siggraph '97 Course notes: Physically Based Modeling](http://www.cs.cmu.edu/~baraff/sigcourse/index.html)**
- **[Physics-Based Animation (2005)](https://iphys.files.wordpress.com/2020/01/erleben.ea05.pdf)** Classic textbook.
- **[Foundations of Physically Based Modeling and Animation (2017)](https://www.amazon.com/Foundations-Physically-Based-Modeling-Animation/dp/1482234602)** (Available in Chinese as [基于物理的建模与动画](https://book.douban.com/subject/35287308/))
- **[Computer Animation: Algorithms and Techniques (2012)](https://www.amazon.com/Computer-Animation-Algorithms-Rick-Parent-ebook/dp/B0094DY2XU)** (Available in Chinese as [计算机动画算法与技术](https://book.douban.com/subject/30369027/))
- **[Physics-Based Simulation](https://phys-sim-book.github.io/)** by Minchen Li & Chenfanfu Jiang.
- **Fluid Mechanics:**
  - *[Fluid Engine Development](https://www.routledge.com/Fluid-Engine-Development/Kim/p/book/9781498719926)* by Doyub Kim. Code: [Fluid Engine Dev](https://github.com/doyubkim/fluid-engine-dev). (Chinese translation available).
  - *[Fluid Simulation for Computer Graphics](https://www.routledge.com/Fluid-Simulation-for-Computer-Graphics/Bridson/p/book/9781482232837)* by Robert Bridson.
  - *[The Art of Fluid Animation](https://www.josstam.com/publications)* by Jos Stam. (Chinese translation available).
- **Cloth:** *[Cloth Simulation for Computer Graphics](https://www.morganclaypool.com/toc/vcp/9/1)*
- **Mass-Spring, FEM, PBD, Rigid Bodies:** *[Real Time Physics Class Notes](https://matthias-research.github.io/pages/publications/realtimeCoursenotes.pdf)*
- **Game Dev Tutorial:** *[Video Game Physics Tutorial](https://www.toptal.com/game/video-game-physics-part-i-an-introduction-to-rigid-body-dynamics)*
- **[SIGGRAPH 2018 Course: Parallel iterative solvers for real-time elastic deformations](http://www.cse.chalmers.se/~marcof/publication/sa2018course/)** Marco Fratarcangeli, Huamin Wang, Yin Yang.
- **[SIGGRAPH 2020 Course: Dynamic Deformables: Implementation and Production Practicalities](http://www.tkim.graphics/DYNAMIC_DEFORMABLES/)** Theodore Kim, David Eberle.

**Recommended Papers from GAMES103 (by Huamin Wang):**
- **Rigid Bodies:** Witkin and Baraff. 2001. Physically Based Modeling – Rigid Body Dynamics. SIGGRAPH Courses.
- **Shape Matching:** Muller et al. 2005. Meshless Deformations Based on Shape Matching. TOG.
- **Implicit Integration Pioneers:** Baraff and Witkin. 1998. Large Step in Cloth Simulation. SIGGRAPH.
- **Cloth:** Bridson et al. 2003. Simulation of Clothing with Folds and Wrinkles. SCA.
- **Cloth:** Bergou et al. 2006. A Quadratic Bending Model for Inextensible Surfaces. SCA.
- **PBD Improvement:** Muller. 2008. Hierarchical Position Based Dynamics. VRIPHYS.
- **Projective Dynamics:** Bouaziz et al. 2014. Projective Dynamics: Fusing Constraint Projections for Fast Simulation. TOG.
- **Constraints:** Tournier et al. 2015. Stable Constrained Dynamics. TOG.

- **[UBC CPSC 533d Animation Physics Reading List](https://www.cs.ubc.ca/~rbridson/courses/533d-winter-2005/reading.html)**
- **[Game Developer's Book List](https://github.com/Asuka109/GameProgramBooks)** *(Notes mostly in Chinese)*

*(To be continued...)*

## 5 Topics & Methods

**Rigid Body**
- [Interactive Simulation of Rigid Body Dynamics in Computer Graphics](http://diglib.eg.org/bitstream/handle/10.2312/conf.EG2012.stars.095-134/095-134.pdf?sequence=1&isAllowed=y)
- [Featherstone: Rigid Body Dynamics Algorithms](https://link.springer.com/book/10.1007/978-1-4899-7560-7)
- [SIGGRAPH'21 Course: Contact and Friction Simulation for Computer Graphics](https://siggraphcontact.github.io/) by Sheldon Andrews & Kenny Erleben.

**Position Based Dynamics** - [A Survey on Position-Based Simulation Methods in Computer Graphics](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.491.1850&rep=rep1&type=pdf)

**MPM**
- [The Material Point Method for Simulating Continuum Materials](https://www.math.ucla.edu/~cffjiang/research/mpmcourse/mpmcourse.pdf)

**FEM**
- [FEM Simulation of 3D Deformable Solids: A practitioner's guide to theory, discretization and model reduction](http://www.femdefo.org/)

**Energy Optimization Perspective** (Fast Mass-Spring, Projective Dynamics, Quasi-Newton, ADMM)
- [Tiantian Liu's 2019 USTC Summer Course Lecture](https://www.bilibili.com/video/BV1hM4y1L7VY?p=5) *(in Chinese)*

**SPH**
- [Eurographics Tutorial 2019: Smoothed Particle Hydrodynamics Techniques for the Physics Based Simulation of Fluids and Solids](https://interactivecomputergraphics.github.io/SPH-Tutorial/) Dan Koschier, Jan Bender, Barbara Solenthaler, Matthias Teschner. 

**USTC Summer School - Physics Simulation Lectures *(all in Chinese)***
- [Official Site](http://staff.ustc.edu.cn/~renjiec/SummerSchool_2022/index.html) | [Bilibili Videos](https://space.bilibili.com/1598639097/)
- 2014 [Weiwei Xu] [Fast Elastic Deformation Simulation Techniques](https://www.bilibili.com/video/BV1gf4y1G7CZ?p=5)
- 2016 [Jin Huang] [Linearization and Dimensionality Reduction in Elastic Simulation](https://www.bilibili.com/video/BV1m44y1k7L4?p=10)
- 2017 [Paul Kry] [Physics Based Computer Animation Fundamentals](https://www.bilibili.com/video/BV1364y1v7Rv?p=38) *(English audio possible, hosted on Bilibili)*
- 2018 [Juyong Zhang] [Numerical Optimization in Geometric Optimization and Physics Simulation](https://www.bilibili.com/video/BV1DL4y1e7N2?p=7)
- 2019 [Tiantian Liu] [Towards Real-time Simulation of Deformable Objects](https://www.bilibili.com/video/BV1hM4y1L7VY?p=5)
- 2021 [Bo Ren] [Graphics Multi-fluid Simulation Using Lagrangian Particle Methods](https://www.bilibili.com/video/BV1Kf4y157WW?p=8)
- 2021 [Xiaopei Liu] [High-Performance Visual Fluid Computing and Applications](https://www.bilibili.com/video/BV1Kf4y157WW?p=9)
- 2021 [Huamin Wang] [Real-Time Cloth Simulation on GPUs](https://www.bilibili.com/video/BV1Kf4y157WW?p=10)
- 2021 [Ye Kuang, Jiancheng Liu] [Taichi Programming Language and Differentiable Physics Simulation](https://www.bilibili.com/video/BV1Kf4y157WW?p=21)

*(To be continued...)*

## 6 Code & Tools

- [Code Replicability in Computer Graphics](https://replicability.graphics/): Collection of SIGGRAPH/TOG paper source codes.
- [NumericalProjectsCollections](https://github.com/clatterrr/NumericalProjectsCollections): Open-source CG code curated by community members.

**Open Source Engines & Libraries:**
- **Taichi:** [Taichi Graphics](https://taichi.graphics/) High-performance graphics programming language.
- **ZENO:** [ZENO](https://github.com/zenustech/zeno) Node-based 3D engine by ZenoTech.
- **libigl:** [libigl](https://libigl.github.io/) Lightweight geometry processing library for researchers.
- **Box2D:** [Box2D](http://www.box2d.org/) Classic 2D physics engine.
- **ODE:** [Open Dynamics Engine](http://ode.org/) Classic rigid body library.
- **Bullet/pyBullet:** [Bullet engine](https://pybullet.org/wordpress/) 3D physics engine (rigid/soft bodies) with C++/Python interfaces.
- **DART:** [Dynamic Animation and Robotics Toolkit](https://dartsim.github.io/index.html) Robotics simulation & RL.
- **PhysX / FleX:** [PhysX](https://developer.nvidia.com/gameworks-physx-overview) | [FleX](https://developer.nvidia.com/flex) Open-sourced NVIDIA game physics engines.
- **ARCSim:** [ARCSim](http://graphics.berkeley.edu/resources/ARCSim/index.html) Adaptive Refining and Coarsening Simulator for cloth.
- **OpenCloth:** [OpenCloth](https://github.com/mmmovania/opencloth) Cloth simulation.
- **Pinocchio:** [Pinocchio](https://github.com/stack-of-tasks/pinocchio) Robotics simulation.
- **MuJoCo:** [mujoco.org](https://mujoco.org/) Robotics simulation (generalized coordinates), open-sourced by DeepMind.
- **ReactPhysics3D:** [www.reactphysics3d.com](https://www.reactphysics3d.com/) Rigid bodies.
- **Simbody:** [Simbody](https://simtk.org/projects/simbody/) Multibody dynamics, biomechanics.
- **Chrono:** [Project Chrono](https://projectchrono.org/) Multibody dynamics, FEM, vehicles.
- **IPC:** [IPC](https://github.com/ipc-sim/IPC) Incremental Potential Contact.
- **RigidBodyDynamics.jl:** [RigidBodyDynamics.jl](https://github.com/JuliaRobotics/RigidBodyDynamics.jl) Rigid body dynamics in Julia.
- **RBDL:** [RBDL](https://github.com/rbdl/rbdl) Rigid Body Dynamics Library (implements Featherstone's algorithms).
- **GEAR:** [GEAR](https://github.com/junggon/gear) Multibody dynamics library based on Lie groups/spatial algebra.
- **PBD:** [PositionBasedDynamics](https://github.com/InteractiveComputerGraphics/PositionBasedDynamics)
- **SPH:** [SPlisHSPlasH](https://github.com/InteractiveComputerGraphics/SPlisHSPlasH)
- **Fluid Engine Dev:** [Fluid Engine Dev](https://github.com/doyubkim/fluid-engine-dev) Fluid simulation library.
- **PhysBAM:** [PhysBAM](http://physbam.stanford.edu/) A comprehensive physics simulation library (rigid, deformable, fluids, cloth, FSI, etc.).
- **mantaflow:** [mantaflow](http://mantaflow.com/index.html) Extensible fluid simulation framework.
- **Vega:** [VEGA FEM LIBRARY](http://barbic.usc.edu/vega/) FEM simulation.
- **NVIDIA Warp:** [NVIDIA Warp](https://nvidia.github.io/warp/) High-performance Python framework for GPU simulation by Miles Macklin.
- **David.li:** [david.li](http://david.li/) WebGL physics simulation experiments.
- **SimpleSimulationEngine:** [SimpleSimulationEngine](https://github.com/ProkopHapala/SimpleSimulationEngine) Simulation/numerical library with C++/Python/Web interfaces.
- **Multibody Survey:** [Survey of Multibody Dynamics Software](http://www.cs.rpi.edu/~trink/sim_packages.html)
- **Matrix Calculus:** [matrixcalculus.org](http://www.matrixcalculus.org/) Online matrix calculus tool.

**Commercial Software:**
- [Houdini](https://www.sidefx.com/)
- [Blender](https://www.blender.org/) (Open Source / Free)
- [Maya](https://www.autodesk.com/products/maya/)
- [Unity](https://unity.com/)
- [Unreal Engine](https://www.unrealengine.com/)

**Solvers:**
- **Eigen:** [eigen.tuxfamily.org](https://eigen.tuxfamily.org/) C++ template library for linear algebra (dense/sparse).
- **Intel MKL:** [Intel oneAPI Math Kernel Library](https://www.intel.com/content/www/us/en/developer/tools/oneapi/onemkl.html) 
- **PARDISO:** [PARDISO](https://www.pardiso-project.org/) Large-scale sparse linear system solver (C/C++, Julia, Fortran, Matlab).
- **SuiteSparse:** [SuiteSparse](https://people.engr.tamu.edu/davis/suitesparse.html) Large-scale sparse linear system solver.

*(To be continued...)*

## 7 Conferences & Journals

### Conferences
| Abbreviation | Full Name |
| :--- | :--- |
| SIGGRAPH / SIGGRAPH ASIA | [ACM Special Interest Group on Computer Graphics](https://www.siggraph.org/) |
| Eurographics | [Annual Conference of the European Association for Computer Graphics](https://www.eg.org/wp/) |
| PG | [Pacific Conference on Computer Graphics and Applications](https://pg2022.org/) |
| SCA | [ACM SIGGRAPH/Eurographics Symposium on Computer Animation](https://computeranimation.org/) |
| I3D | [ACM SIGGRAPH Symposium on Interactive 3D Graphics and Games](http://i3dsymposium.github.io/) |
| MIG | [The ACM SIGGRAPH Conference on Motion, Interaction and Games](https://mig2021.inria.fr/submission/) |
| IEEE VR | [IEEE Conference on Virtual Reality and 3D User Interfaces](https://ieeevr.org/) |

<br/> 

### Journals

| Abbreviation | Full Name | IF | JCR Quartile |
| :--- | :--- | :---: | :---: |
| TOG | [ACM Transactions on Graphics](https://dl.acm.org/journal/tog) | 9.5 | Q1 |
| TVCG | [IEEE Transactions on Visualization and Computer Graphics](https://www.computer.org/csdl/journal/tg) | 5.2 | Q1 |
| CGF | [Computer Graphics Forum](https://onlinelibrary.wiley.com/journal/14678659) | 2.7 | Q2 |
| C&G | [Computers & Graphics](https://www.journals.elsevier.com/computers-and-graphics) | 2.5 | Q2 |
| TVC | [The Visual Computer](https://www.springer.com/journal/371) | 3.0 | Q2 |
| CAVW | [Computer Animation and Virtual Worlds](https://onlinelibrary.wiley.com/journal/1546427x) | 1.5 | Q3 |
| GM| [Graphical Models](http://www.elsevier.com/locate/gmod) | 1.5 | Q3 |
| IEEE CG&A | [IEEE Computer Applications and Graphics](https://www.computer.org/csdl/magazine/cg) | 2.0 | Q3 |
| CVMJ | [Computational Visual Media](https://www.springer.com/journal/41095/) | 12.9 | Q1 |
| PACMCGIT | [Proceedings of the ACM on Computer Graphics and Interactive Techniques](https://dl.acm.org/journal/pacmcgit) | 2.3 | Q3 |