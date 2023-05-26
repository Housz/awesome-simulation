整理一下基于物理的模拟/动画（Physics based simulation/animation）方向的课程、研究者、文献和代码等资源。持续更新，欢迎补充！

[GitHub: github.com/Housz/GraphicsSimulation](https://github.com/Housz/GraphicsSimulation)

## 1 课程

图形学入门：

【闫令琪】[GAMES101: 现代计算机图形学入门](https://sites.cs.ucsb.edu/~lingqi/teaching/games101.html)

【刘利刚】[2020年中国科学技术大学《计算机图形学》本科课程](https://www.bilibili.com/video/BV1iT4y1o7oM)

【[OpenGL](https://learnopengl-cn.github.io/)】[LearnOpenGL CN (learnopengl-cn.github.io)](https://learnopengl-cn.github.io/) 最好的OpenGL入门教程

物理模拟：

【王华民】[GAMES103：基于物理的计算机动画入门](http://games-cn.org/games103/) 包括：数学背景知识、刚体、质点弹簧系统、约束、碰撞、软体与有限元、流体等，对新手比较友好。四个作业（刚体、布料、柔性体、流体）采用Unity平台，较容易上手。

【胡渊鸣】[GAMES201：高级物理引擎实战指南2020](http://games-cn.org/games201/) 深度广度都非常高，若没有数值计算背景上手难度较大。包括拉格朗日视角、欧拉视角、混合欧拉-拉格朗日视角、高性能物理引擎等话题。

【刘天添】[太极图形课](https://space.bilibili.com/1779922645?from=search&seid=3236551890279933972&spm_id_from=333.337.0.0) 采用Taichi语言的图形学课程。包括：图形学介绍、编程基础、Taichi数据结构和性能、动画基础、光线追踪、弹性体（时间积分、有限元、能量求导、隐式积分与线性系统求解）、流体（拉格朗日视角、欧拉视角）等。有作业和答疑。

【王希】[GAMES104-现代游戏引擎](https://www.bilibili.com/video/BV1oU4y1R7Km) 第10、11课介绍游戏引擎中的物理系统；第8、9课介绍游戏引擎中的动画技术。

【Ladislav Kavan】[CIS563 Physics based Animation (2014)](https://www.youtube.com/watch?v=Q0D3tUViO6Y&list=PL_a9tY9IhJuM2dIVCH_ZC0Pn5871eDY7_&ab_channel=LadislavKavan) Ladislav的课都是手推公式，很细致。包括：质点弹簧系统、PBD、Shape Matching、PDE基础、FEM、Projective Dynamics、刚体、碰撞等。[CIS563 Physics based Animation (2015)](https://www.youtube.com/watch?v=Zw81lwV65wk&list=PL_a9tY9IhJuPuw5nu-WU7mG8T8MiX4JnY&ab_channel=LadislavKavan) 新增了流体等内容。[补充内容（刘天添）](https://www.youtube.com/user/ltt1598/videos)[CS6660 Physics based Animation (2017)](https://www.youtube.com/watch?v=sSKyQIxdhdA&list=PL_a9tY9IhJuPc7e6r-3DMw_PbYbloKoWM&ab_channel=LadislavKavan) 加入了拉格朗日/哈密顿力学的视角。

【Eitan Grinspun】[Animation and CGI Motion](https://learning.edx.org/course/course-v1:ColumbiaX+CSMM.104x+1T2017/home) （仅在edX平台）Eitan大神讲得很细，手推公式，对初学者非常友好。包括：OED数值积分入门，拉格朗日力学视角，碰撞、接触与摩擦，连续介质力学，有限元，刚体，薄壳与布料，绳子与头发，流体等。

【Matthias Müller】[Ten Minute Physics](https://matthias-research.github.io/pages/tenMinutePhysics/index.html) （更新中）特点是提供JavaScript实现代码，容易上手。

【Adam Bargteil】[SIGGRAPH&#39;19 Course: An Introduction to Physics-Based Animation](https://www.youtube.com/watch?v=b_WJ-HwalwU&ab_channel=ACMSIGGRAPH) Siggraph2019课程，介绍了物理模拟的基本概念，有配套文档。

【David I.W. Levin】[CSC417/CSC2549 Physics-Based Animation](https://github.com/dilevin/CSC417-physics-based-animation)[YouTube](https://www.youtube.com/channel/UCIM0HrQVDcUYdrZvSwuUJgA/videos)[bilibili](https://www.bilibili.com/video/BV1GB4y1u72S) 拉格朗日力学，质点弹簧系统，FEM，刚体、流体。

【Doug L. James】[CS 5643: Physically Based Animation for Computer Graphics (2015)](https://www.cs.cornell.edu/courses/cs5643/2015sp/) 非常全面的课程，列出了每个方向的经典文献。包括：粒子、矩阵计算、约束动力学、SPH流体、PBF流体、数值积分、隐式求解、PBD、碰撞、刚体、刚体声音、流体、共轭梯度、Shape Matching、破碎、烟雾水体和火的控制、噪声与湍流、动画声音等。[Doug的其他课程](http://graphics.stanford.edu/~djames/teaching/)：[CS 448Z: Physically Based Animation and Sound (2021)](http://graphics.stanford.edu/courses/cs448z/)，[CS 248: Interactive Computer Graphics (2022)](https://gfxcourses.stanford.edu/cs248/winter22)，[CS 348C: Computer Graphics: Animation and Simulation (2022)](http://graphics.stanford.edu/courses/cs348c/)

【Jernej Barbič】[CSCI 520 Computer Animation and Simulation](https://viterbi-web.usc.edu/~jbarbic/cs520-s22/)

数学基础：

矩阵计算基础：[GAMES103数学基础](http://games-cn.org/games103/)[3Blue1Brown线性代数的本质](https://www.bilibili.com/video/BV1ys411472E?spm_id_from=333.999.0.0)[矩阵求导术](https://zhuanlan.zhihu.com/p/24709748)[Numerical Recipes](http://numerical.recipes/book/book.html)[wiki Matrix_calculus](https://en.m.wikipedia.org/wiki/Matrix_calculus)

数值分析基础：[数值分析2020春](https://www.bilibili.com/video/BV18741177td) 苏州大学张亚楠老师，深入浅出。教材参考李庆扬《数值分析》第四/五版。

数值分析进阶：[数值分析 中科大](https://www.bilibili.com/video/BV1T4411D7x5) 布朗大学舒其望。最强中文数值课程。

最优化基础：[最优化理论与方法](https://space.bilibili.com/507629580) 上海财经崔雪婷老师。参考教材Stephan Boyd《凸优化》，Jorge Nocedal《Numerical Optimization》等。

最优化进阶：[Boyd斯坦福公开课](https://www.bilibili.com/video/BV1Pg4y187Ed) 优化之神Boyd带你谈笑风生。

科学计算基础：[EAS205 Applications of Scientific Computation (2014)](https://www.youtube.com/watch?v=Ikl1wnwIOmM&list=PL_a9tY9IhJuPDEDq97tq0uKXpsTZYBIXe&ab_channel=LadislavKavan) Ladislav Kavan的科学计算基础课程，包括向量矩阵计算、线性变换、线性系统、群论入门、向量空间、最小二乘、奇异值分解等。

## 2 研究者、团队

[胡渊鸣](https://yuanming.taichi.graphics/) （MIT, 太极图形） [@胡渊鸣](https://www.zhihu.com/people/19787805e0d1f80fe5501ec60be84d6a)[99行代码的《冰雪奇缘》](https://zhuanlan.zhihu.com/p/97700605)

[刘利刚](http://staff.ustc.edu.cn/~lgliu/) （中科大）

[刘天添](https://tiantianliu.cn/) （UPenn, 太极图形） [@天天添一点儿](https://www.zhihu.com/people/b71d9a706d0216654be0f16cfd0b2b5a)

[王华民](https://web.cse.ohio-state.edu/~wang.3602/index.html) （Ohio State University，style3d） [@wanghmin](https://www.zhihu.com/people/ca6e5cf45df33e1ca946aab6a5295ad2)

[蒋陈凡夫](https://www.math.ucla.edu/~cffjiang/) （UCLA） [@蒋陈凡夫](https://www.zhihu.com/people/346d9a6d4914ba9d4f1fcf7b4e41e514)[从转系生到终身教授：十二年图形学物理模拟的自我回顾](https://zhuanlan.zhihu.com/p/560415998)

[张心欣](https://zhxx1987.github.io/) （UBC, 泽森科工） [@张心欣](https://www.zhihu.com/people/9d0cd62f9071c2b003b2ef7b017fb7f5)

[李旻辰](https://www.math.ucla.edu/~minchen/) （UCLA） [@Minchern](https://www.zhihu.com/people/9f3ee58deeb19551bd92d9591e4503d7)

[费昀](http://yunfei.work/) （Adobe） [@Raymond Fei](https://www.zhihu.com/people/ecf74d1b95762c56eebfe55935655e26)

[任博](http://ren-bo.net/) （南开）

[黄劲](http://www.cad.zju.edu.cn/home/hj/index.xml) （浙大）

[唐敏](https://min-tang.github.io/home/Data/contact-ch.html)（浙大）

[高明](https://mingg13.github.io/) （Tencent）

[朱博](https://cs.dartmouth.edu/~bozhu/)（Dartmouth）

[Libin Liu](http://libliu.info/)（北大）

[Ladislav Kavan](https://www.cs.utah.edu/~ladislav/)（University of Utah, Facebook）柔性体、数值方法等

[Eitan Grinspun](https://www.dgp.toronto.edu/~eitan/)（University of Toronto）几何、物理等

[Robert Bridson](https://www.cs.ubc.ca/~rbridson/)（UBC）动画、物理等

[David Baraff](http://www.cs.cmu.edu/~baraff/)；[Andrew Witkin](https://www.cs.cmu.edu/afs/cs.cmu.edu/user/aw/www/index.html) （CMU, Pixar）两位上古大神，宗师级人物

[Demetri Terzopoulos](http://web.cs.ucla.edu/~dt/)（UCLA）

[Joseph Teran](https://www.math.ucla.edu/~jteran/)（UCLA）

[Markus Gross](https://cgl.ethz.ch/people/grossm/) （ETH Zurich）

[Jos Stam](https://www.josstam.com/)（Nvidia）

[Jan Bender](https://animation.rwth-aachen.de/person/1/)（RWTH Aachen University）SPH

[Matthias Müller](https://matthias-research.github.io/pages/) ； [Miles Macklin](http://blog.mmacklin.com/) （NVIDIA）PBD

[Dinesh K. Pai](https://sensorimotor.cs.ubc.ca/pai/) （UBC）

[Paul G. Kry](https://www.cs.mcgill.ca/~kry/) （McGill University）[Sheldon Andrews](http://profs.etsmtl.ca/sandrews/) （École de technologie supérieure） 刚体、接触摩擦等

[Jernej Barbic](https://viterbi-web.usc.edu/~jbarbic/)（USC）

[Kenny Erleben](https://iphys.wordpress.com/)（University of Copenhagen）刚体，机器人

[Jeff Trinkle](https://engineering.lehigh.edu/faculty/jeffrey-c-trinkle) （Lehigh University）刚体，机器人

[Roy Featherstone](http://royfeatherstone.org/) （Italian Institute of Technology）刚体，机器人

[C. Karen Liu](https://ckllab.stanford.edu/) （Stanford）机器人，强化学习

[Xue Bin (Jason) Peng](https://xbpeng.github.io/) （UC Berkeley）机器人，强化学习

[Shinjiro Sueda](https://people.engr.tamu.edu/sueda/index.html) （Texas A&M University）机器人、弹性体

[David I.W. Levin](http://142.93.146.228/researchdb/#aboutme) （University of Toronto）

[Doug L. James](http://graphics.stanford.edu/~djames/)（Stanford）

[Theodore Kim](https://www.tkim.graphics/)（Yale）

[Matthias Teschner](https://cg.informatik.uni-freiburg.de/teschner.htm)（University of Freiburg）

[Eftychios Sifakis](https://pages.cs.wisc.edu/~sifakis/)（UW-Madison）


[@禹鹏](https://www.zhihu.com/people/87feef9df8867f554d7e3b05ef36fe2e) 大佬整理的[物理仿真谱系](https://naotu.baidu.com/file/eb1a5ebf45eac4eb4c783aae20bf662e?token=6333ba7d098d633c)

未完待续......

研究团队

[Stanford Computer Graphics Laboratory](https://graphics.stanford.edu/)（Stanford）

[Dynamic Graphics Project](https://www.dgp.toronto.edu/) （University of Toronto）

[Computer Graphics University of California - Berkeley](http://graphics.berkeley.edu/) （Berkeley）

[Computational Sciences Group](http://www.computationalsciences.org/)（KAUST）

[Carnegie Mellon Graphics Lab](http://graphics.cs.cmu.edu/)（CMU）

[Pixar Research](https://graphics.pixar.com/)（Pixar）

## 3 资源集合

【中文图形学交流平台】[计算机图形学与混合现实研讨会 – GAMES: Graphics And Mixed Environment Seminar (games-cn.org)](http://games-cn.org/)

【中科大《计算机图形学前沿》暑期课程】[官网](http://staff.ustc.edu.cn/~lgliu/Courses/SummerSchool/USTC-summer-school.html)[Bilibili](https://space.bilibili.com/1598639097)

【物理仿真论文集合】[Physics-Based Animation (physicsbasedanimation.com)](http://www.physicsbasedanimation.com/)

【图形学论文集合】[Resource for Computer Graphics - Ke-Sen Huang&#39;s Home Page (realtimerendering.com)](http://kesen.realtimerendering.com/)

【SIGGRAPH Courses等资源】 [https://blog.selfshadow.com/](https://blog.selfshadow.com/)

【物理仿真论文集合】[Computer Graphics and Simulation | Research Results](https://iphys.wordpress.com/)

【物理仿真代码 SPH PBD等】[Home (interactive-graphics.de)](https://interactive-graphics.de/)

【知乎专栏】 [GraphiCon图形控](https://zhuanlan.zhihu.com/graphicon) - 知乎 (zhihu.com)

未完待续......

## 4 入门文献

【Siggraph '97 Course notes】[Physically Based Modeling (cmu.edu)](http://www.cs.cmu.edu/~baraff/sigcourse/index.html)

【经典物理模拟入门书】[Physics-Based Animation](https://iphys.files.wordpress.com/2020/01/erleben.ea05.pdf) (2005)

【物理模拟入门书】[Foundations of Physically Based Modeling and Animation](https://www.amazon.com/Foundations-Physically-Based-Modeling-Animation/dp/1482234602) (2017)

中文版：[基于物理的建模与动画](https://book.douban.com/subject/35287308/) 目录：[白如冰](https://zhuanlan.zhihu.com/p/342390945)

【计算机动画入门书】[Computer Animation: Algorithms and Techniques](https://www.amazon.com/Computer-Animation-Algorithms-Rick-Parent-ebook/dp/B0094DY2XU) (2012) 中文版：[计算机动画算法与技术](https://book.douban.com/subject/30369027/)

【布料】[Cloth Simulation for Computer Graphics](https://www.morganclaypool.com/toc/vcp/9/1)

【质点弹簧、有限元、PBD、刚体】[Real Time Physics Class Notes](https://matthias-research.github.io/pages/publications/realtimeCoursenotes.pdf)

【一个游戏开发大神写的教程】[Video Game Physics Tutorial](https://www.toptal.com/game/video-game-physics-part-i-an-introduction-to-rigid-body-dynamics)

【SIGGRAPH Courses, 2018 软体仿真实时并行求解】[Parallel iterative solvers for real-time elastic deformations](http://www.cse.chalmers.se/~marcof/publication/sa2018course/)Marco Fratarcangeli, Huamin Wang, Yin Yang

【SIGGRAPH Courses, 2020 软体】[Dynamic Deformables: Implementation and Production Practicalities](http://www.tkim.graphics/DYNAMIC_DEFORMABLES/)Theodore Kim, David Eberle

GAMES103 课程王华民老师推荐的文献：

【刚体】Witkin and Baraff. 2001. Physically Based Modeling – Rigid Body Dynamics. SIGGRAPH Courses.

【Shape Matching】Muller et al. 2005. Meshless Deformations Based on Shape Matching. TOG (SIGGRAPH).

【隐式积分的先驱】Baraff and Witkin. 1998. Large Step in Cloth Simulation. SIGGRAPH.

【布料】Bridson et al. 2003. Simulation of Clothing with Folds and Wrinkles. SCA.

【布料】Bergou et al. 2006. A Quadratic Bending Model for Inextensible Surfaces. SCA.

【PBD改进】Muller. 2008. Hierarchical Position Based Dynamics. VRIPHYS.

【PD】Bouaziz et al. 2014. Projective Dynamics: Fusing Constraint Projections for Fast Simulation. TOG (SIGGRAPH).

【约束】Tournier et al. 2015. Stable Constrained Dynamics. TOG (SIGGRAPH).

[UBC CPSC 533d Animation Physics 课程推荐文献列表](https://www.cs.ubc.ca/~rbridson/courses/533d-winter-2005/reading.html)

[游戏开发者的书单](https://github.com/Asuka109/GameProgramBooks)

未完待续......

## 5 Topics & Methods

刚体（Rigid Body）

[Interactive Simulation of Rigid Body Dynamics in Computer Graphics](http://diglib.eg.org/bitstream/handle/10.2312/conf.EG2012.stars.095-134/095-134.pdf?sequence=1&isAllowed=y)

[Featherstone: Rigid Body Dynamics Algorithms](https://link.springer.com/book/10.1007/978-1-4899-7560-7)

[Sheldon Andrews &amp; Kenny Erleben SIGGRAPH&#39;21 Course: Contact and Friction Simulation for Computer Graphics](https://siggraphcontact.github.io/) Siggraph2021课程，介绍接触与摩擦。包括：接触和摩擦的理论、算法，线性互补问题（LCP）等。

Position Based Dynamics

[A Survey on Position-Based Simulation Methods in Computer Graphics](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.491.1850&rep=rep1&type=pdf)

MPM

[The Material Point Method for Simulating Continuum Materials](https://www.math.ucla.edu/~cffjiang/research/mpmcourse/mpmcourse.pdf)

FEM

[FEM Simulation of 3D Deformable Solids: A practitioner&#39;s guide to theory, discretization and model reduction](http://www.femdefo.org/)

能量优化视角（Fast Mass-Spring, Projective Dynamics, Quasi-Newton, ADMM ......）

[2019年（第八届）中国科学技术大学《计算机图形学前沿》暑期课程 P5 刘天添](https://www.bilibili.com/video/BV1hM4y1L7VY?p=5)

流体（Fluid）

[Fluid Engine Development](https://www.routledge.com/Fluid-Engine-Development/Kim/p/book/9781498719926) 配套流体模拟库：[Fluid Engine Dev](https://github.com/doyubkim/fluid-engine-dev)

SPH

【Eurographics Tutorial, 2019】[Smoothed Particle Hydrodynamics Techniques for the Physics Based Simulation of Fluids and Solids](https://interactivecomputergraphics.github.io/SPH-Tutorial/)Dan Koschier, Jan Bender, Barbara Solenthaler, Matthias Teschner  包括：SPH理论基础、近邻搜索、不可压缩性、边界处理、多相流体、粘度、涡度、SPlisHSPlasH开源库、可变形固体、刚体、数据驱动技术。

中科大暑期课程计算机图形学前沿进展 物理模拟相关讲座

官网：[计算机图形学前沿进展](http://staff.ustc.edu.cn/~renjiec/SummerSchool_2022/index.html)    视频：[哔哩哔哩](https://space.bilibili.com/1598639097/)

2014【许威威】[快速弹性形变物理仿真技术](https://www.bilibili.com/video/BV1gf4y1G7CZ?p=5&vd_source=69468ebad779e1a70aa2d793ae97c2f0)

2016【黄劲】[弹性模拟中的线性化与降维](https://www.bilibili.com/video/BV1m44y1k7L4?p=10&vd_source=69468ebad779e1a70aa2d793ae97c2f0)

2017【Paul Kry】[Physics Based Computer Animation Fundamentals](https://www.bilibili.com/video/BV1364y1v7Rv?p=38&vd_source=69468ebad779e1a70aa2d793ae97c2f0)

2018【张举勇】[几何优化与物理模拟中的数值优化算法](https://www.bilibili.com/video/BV1DL4y1e7N2?p=7&vd_source=69468ebad779e1a70aa2d793ae97c2f0)

2019【刘天添】[Towards Real-time Simulation of Deformable Objects](https://www.bilibili.com/video/BV1hM4y1L7VY?p=5&vd_source=69468ebad779e1a70aa2d793ae97c2f0)

2021【任博】[使用拉格朗日粒子方法的图形学多流体模拟](https://www.bilibili.com/video/BV1Kf4y157WW?p=8&vd_source=69468ebad779e1a70aa2d793ae97c2f0)

2021【刘晓培】[高性能可视流体计算及其应用](https://www.bilibili.com/video/BV1Kf4y157WW?p=9&vd_source=69468ebad779e1a70aa2d793ae97c2f0)

2021【王华民】[Real-Time Cloth Simulation on GPUs](https://www.bilibili.com/video/BV1Kf4y157WW?p=10&vd_source=69468ebad779e1a70aa2d793ae97c2f0)

2021【匡冶, 刘剑成】[太极编程语言与可微物理模拟](https://www.bilibili.com/video/BV1Kf4y157WW?p=21&vd_source=69468ebad779e1a70aa2d793ae97c2f0)

未完待续......

## 6 代码与工具

[Code Replicability in Computer Graphics](https://replicability.graphics/)：搜集SIGGRAPH/TOG论文的代码

[NumericalProjectsCollections](https://github.com/clatterrr/NumericalProjectsCollections)： [@胡虎互护呼](https://www.zhihu.com/people/81508c1d5969bb797f8e3f9c94acf68b) 大佬整理的图形学领域开源代码

开源引擎/代码库：

Taichi：[Taichi Graphics](https://taichi.graphics/) 太极图形编程语言 [@太极图形](https://www.zhihu.com/people/458c690a3722fd38ffd3d3dcadcf8b13)

ZENO：[ZENO](https://github.com/zenustech/zeno)：泽森ZENO开源引擎 [@张心欣](https://www.zhihu.com/people/9d0cd62f9071c2b003b2ef7b017fb7f5)

libigl：[https://libigl.github.io/](https://libigl.github.io/) 面向研究者的轻量的几何处理库

Box2D：[http://www.box2d.org/](http://www.box2d.org/) 经典2D物理引擎

OED：[Open Dynamics Engine](http://ode.org/) 经典刚体模拟库

Bullet/pyBullet：[Bullet engine](https://pybullet.org/wordpress/) 3D物理引擎，支持刚体、柔体等，支持C++，python接口

DART：[DART: Dynamic Animation and Robotics Toolkit](https://dartsim.github.io/index.html) 机器人仿真、强化学习

PhysX：[PhysX](https://developer.nvidia.com/gameworks-physx-overview)[FleX](https://developer.nvidia.com/flex) 英伟达游戏引擎，已开源

ARCSim：[ARCSim: Adaptive Refining and Coarsening Simulator](http://graphics.berkeley.edu/resources/ARCSim/index.html) 布料

OpenCloth：[https://github.com/mmmovania/opencloth](https://github.com/mmmovania/opencloth) 布料

Pinocchio：[Pinocchio](https://github.com/stack-of-tasks/pinocchio) 机器人仿真

MuJoCo：[mujoco.org](https://mujoco.org/) 机器人仿真，广义坐标，被DeepMind收购后开源

ReactPhysics3d：[www.reactphysics3d.com](https://www.reactphysics3d.com/) 刚体

Simbody：[simtk.org/projects/simbody/](https://simtk.org/projects/simbody/) 多体动力学、生物力学

Chrono：[https://projectchrono.org/](https://projectchrono.org/) 多体动力学、有限元、车辆

IPC：[https://github.com/ipc-sim/IPC](https://github.com/ipc-sim/IPC)  Incremental Potential Contact

RigidBodyDynamics.jl：[https://github.com/JuliaRobotics/RigidBodyDynamics.jl](https://github.com/JuliaRobotics/RigidBodyDynamics.jl) Julia语言的刚体动力学库

RBDL：[https://github.com/rbdl/rbdl](https://github.com/rbdl/rbdl) 刚体动力学，实现了Featherstone教材内容

GEAR：[https://github.com/junggon/gear](https://github.com/junggon/gear) 基于李群/旋量理论的多体动力学库

PBD：[InteractiveComputerGraphics / PositionBasedDynamics](https://github.com/InteractiveComputerGraphics/PositionBasedDynamics)

SPH：[InteractiveComputerGraphics/SPlisHSPlasH](https://github.com/InteractiveComputerGraphics/SPlisHSPlasH)

Fluid Engine Dev：[Fluid Engine Dev](https://github.com/doyubkim/fluid-engine-dev)：流体模拟库，有配套教材

PhysBAM：[http://physbam.stanford.edu/](http://physbam.stanford.edu/) 一个包罗万象的物理模拟库，包括：刚体、变形体、流体、布料、流固耦合、人体、破碎、火焰、烟雾、头发、肌肉等

mantaflow：[An extensible framework for fluid simulation](http://mantaflow.com/index.html) 流体

Vega：[VEGA FEM LIBRARY](http://barbic.usc.edu/vega/) 有限元

[http://david.li/](http://david.li/) ：一个Web3d环境下的物理效果集合库

SimpleSimulationEngine： [github.com/ProkopHapala/SimpleSimulationEngine](https://github.com/ProkopHapala/SimpleSimulationEngine) 模拟、数值、C++/python/web接口

刚体动力学库搜集：[Survey of Multibody Dynamics Software (rpi.edu)](http://www.cs.rpi.edu/~trink/sim_packages.html)

Matrix Calculus：[http://www.matrixcalculus.org/](http://www.matrixcalculus.org/) 在线矩阵计算

商业软件：

Houdini：[https://www.sidefx.com/](https://www.sidefx.com/)

Blender：[https://www.blender.org/](https://www.blender.org/) 开源、免费

MAYA：[https://www.autodesk.com/products/maya/](https://www.autodesk.com/products/maya/)

Unity：[https://unity.com/](https://unity.com/)

Unreal Engine：[https://www.unrealengine.com/](https://www.unrealengine.com/)

求解器：

Eigen：[eigen.tuxfamily.org](https://eigen.tuxfamily.org/index.php?title=Main_Page) 线性代数库，稠密/稀疏线性系统解算，纯C++头文件实现

Intel MKL：[Intel® oneAPI Math Kernel Library](https://www.intel.com/content/www/us/en/developer/tools/oneapi/onemkl.html) 英特尔的数学核心函数库

PARDISO：[https://www.pardiso-project.org/](https://www.pardiso-project.org/) 大规模稀疏线性系统求解，提供C/C++, Julia, Fortran, Matlab接口

SuiteSparse：[https://people.engr.tamu.edu/davis/suitesparse.html](https://people.engr.tamu.edu/davis/suitesparse.html) 大规模稀疏线性系统求解

未完待续......

## 7 Conferences & Journals

[SIGGRAPH / SIGGRAPH ASIA](https://www.siggraph.org/)

[Eurographics (EG)](https://www.eg.org/wp/)

[Pacific Graphics（PG）](https://pg2022.org/)

[Symposium on Computer Animation (SCA)](https://computeranimation.org/)

[Symposium on Interactive 3D Graphics and Games (I3D)](http://i3dsymposium.github.io/)

[The ACM SIGGRAPH Conference on Motion, Interaction and Games (MIG)](https://mig2021.inria.fr/submission/)

[IEEE Conference on Virtual Reality and 3D User Interfaces (IEEE VR)](https://ieeevr.org/)    



[ACM Transactions on Graphics (TOG)](https://dl.acm.org/journal/tog)

[IEEE Transactions on Visualization and Computer Graphics (TVCG)](https://www.computer.org/csdl/journal/tg)

[Computer Graphics Forum (CGF)](https://onlinelibrary.wiley.com/journal/14678659)

[Computers &amp; Graphics](https://www.journals.elsevier.com/computers-and-graphics)

[The Visual Computer](https://www.springer.com/journal/371)

[Computer Animation and Virtual Worlds](https://onlinelibrary.wiley.com/journal/1546427x)

[Graphical Models](http://www.elsevier.com/locate/gmod)

[IEEE Computer Applications and Graphics](https://www.computer.org/csdl/magazine/cg)

[Computational Visual Media](https://www.springer.com/journal/41095/) (CVMJ)

感谢 [@Xayah](https://www.zhihu.com/people/f85784fe67a5105f265aed3a791f2c8d)[@胡虎互护呼](https://www.zhihu.com/people/81508c1d5969bb797f8e3f9c94acf68b) 的补充！
