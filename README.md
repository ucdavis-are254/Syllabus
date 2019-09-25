---
title: |
    | Syllabus
    | ARE 254: Dynamic Optimization
author: |
    | Mark Agerton
    | [mjagerton@ucdavis.edu](mailto:mjagerton@ucdavis.edu)
date: Fall 2019
# geometry: margin=1in
bibliography: are254.bib
csl: chicago-author-date.csl
colorlinks: true
link-citations: true
linestretch: 1.0
pagetitle: "Syllabus"
numbersections: false
---

# Logistics

**Class meetings** are Monday/Wednesday 10:00--11:50am in the ARE Main Conference Room (SS&H 2102)

**Office Hours** will be Fridays 2-3pm in my office (SS&H 3110), but I'm happy to meet at another time---just ask.

You are all adult graduate students: please call me "Mark."  If you feel more comfortable addressing me as "Dr./Prof. Mark" or "Dr./Prof. Agerton," that's okay, too.

The best way to reach me is via email: [mjagerton@ucdavis.edu](mailto:mjagerton@ucdavis.edu).

We have a Github Organization [ucdavis-are254](https://github.com/ucdavis-are254) that we will use for homeworks on [Github Classroom](https://classroom.github.com/classrooms/55290887-are-254-fall-2019) and discussions via our Github Team [\@ucdavis-are254/2019-fall](https://github.com/orgs/ucdavis-are254/teams/2019-fall). I *highly* encourage you to ask questions via our Github Team and respond to classmates. We will also use a [Canvas page](https://canvas.ucdavis.edu/courses/370582) sometimes.

# Course format

The course will be a lecture/discussion format.

**Homeworks** will generally be due on Mondays, and I suggest that you work in teams of up to 3 people. These will be a **key** opportunity for you to learn. Each Monday, I will ask students to present solutions to their homework.

The majority of your grade will be based on a **final project** applying one or more techniques discussed in the course to a dynamic optimization problem.

# Overview

This is a *methods* course that will introduce you to the analytical and computational methods required to handle single-agent *dynamic* economic problems. These are problems in which *forward-looking* agents' payoffs depend on the *state* of the world, and agents can take *actions* today that affect the state tomorrow. The course is a required part of the resource/environmental sequence and a prerequisite for ARE 277. As much as possible, we will learn analytical and computational methods in parallel, so that what we solve on pen and paper, we also solve on the computer.

# Texts

There are several texts that I will reference throughout the course. I will follow @leonard1992optimal for optimal control. @miranda2002applied is a "required" text carried at the bookstore and has good example problem, but I will also be making use of @judd1998numerical, which is a bit more mathematical.

- Dynamic programming
    + **@stokey1989recursive** is a classic text that covers the theory of dynamic programming. It is a mathematically sophisticated text and lays out the foundations for much of what we'll do in part 2 of the course.
    + **@adda2003dynamic** contains a brief treatment of the theory and numerical methods behind dynamic programming. Chapter 4 discusses how one might estimate the parameters of a dynamic economies by matching moments in the data. Subsequent chapters deal with applications of this in growth, consumption, durable goods, investment, and labor.

- Optimal Control
    + **@leonard1992optimal** is the text we will use to cover optimal control.
    + **@kamien1991dynamic** is another great reference. It builds up optimal control theory from the calculus of variations, which @leonard1992optimal skips.

- Numerical Methods
    + **@miranda2002applied** is the recommended text for the course for computational matters, and you can **access it for free [via the library](https://ebookcentral.proquest.com/lib/ucdavis/detail.action?docID=3338831)**. It is an applied book. It has less detail than @judd1998numerical and references a MATLAB toolbox, but also a great many resource-economics examples.


        ***This course has an optional digital version of the textbook available.*** To access it, go to our [Canvas page](https://canvas.ucdavis.edu/courses/370582) and click on the Bookshelf menu option in Canvas to access your Student IA Portal. Follow the instructions in your portal to access the e-book. *You will have **[free]** trial access until the 14th day of instruction and can choose to opt in or not during that period to retain full access.*

    + **@judd1998numerical** is the standard textbook for numerical methods in economics. If computation of dynamic models or structural estimators will be a part of your research, it's a good reference to own.
    + **@kochenderfer2019algorithms** is a new textbook devoted to applied numerical optimization and offers Julia code examples. Julia examples are available as a [collection of Jupyter notbooks](https://github.com/sisl/algforopt-notebooks)
    + **@nocedal2006numerical** is a more somewhat more rigorous treatment of optimization for smooth problems, and you can access an [electronic version](https://search.library.ucdavis.edu/permalink/f/1ns6oht/TN_springer_series978-0-387-40065-5) for free through the UC Davis library.

# Software

## Julia

The course will use [Julia](https://julialang.org/), a free and open source scientific computing language.

You can use any text editor to write and edit Julia code---you do not need a special GUI as with Stata or MATLAB. However, I suggest you use one of the following options:

- The text editor [Atom](https://atom.io/) with the [Juno](https://junolab.org/) suite of packages (this is what I use)
- [Jupyter notebooks](https://jupyter.org/) and the [IJulia.jl](https://github.com/JuliaLang/IJulia.jl) package
- Microsoft's [Visual Studio Code](https://code.visualstudio.com/) with the Julia [extension](https://marketplace.visualstudio.com/items?itemName=julialang.language-julia)

The Quantecon [Julia lectures](https://lectures.quantecon.org/jl/) are a great resource for getting started, and the [QuantEcon notes](https://notes.quantecon.org/) have some excellent examples and replications.

## Git

You will also need to create an account at [Github](https://github.com/) to participate in our [Github Classroom](https://classroom.github.com/classrooms/55290887-are-254-fall-2019). I suggest you I suggest you register for the [Github Student Developer Pack](https://education.github.com/pack) and install the command-line program [Git](https://git-scm.com/). GUIs for Git include [Github Desktop](https://desktop.github.com), [Git Kraken](https://www.gitkraken.com/) (free with the Github student developer pack), and [Sublime Merge](https://www.sublimemerge.com/).


# Student resources

Student resources on academic support, health & wellness, career & internships, and campus community are available at <https://ebeler.faculty.ucdavis.edu/resources/faq-student-resources/>.

# Students with disabilities

If you have a documented disability that will impact your work in class, please contact me to discuss your needs. All discussions will remain confidential. Students with disabilities will also need to contact the [Student Disability Center](https://sdc.ucdavis.edu/).

# Academic integrity

I take academic integrity and the [UC Davis Academic Code of Conduct](https://ossja.ucdavis.edu/code-academic-conduct) seriously, and I expect you to as well. My goal is for each of you to succeed in this class and become better economists. The assignments are designed to help you learn together with your peers and do well if you make a good faith effort. That said, I will report issues of academic integrity to the [Office of Student Support and Judicial Affairs (OSSJA)](https://ossja.ucdavis.edu/).

**Plagiarism:** I'm excited for you to have opportunity to do some of your own research and writing. You are creative, intelligent economists. I'm excited for you to incorporate feedback from your peers into your work and explore research by others. However, your work must be your own. Using someone else's work without citing it is *plagiarism* and qualifies as academic misconduct. If you're ever concerned about this, please talk with me. Here's what the OSSJA has to say on plagiarism[^1]:

> *Any time you use the research, ideas, images, analysis, language, etc. of another, you must cite that individual (give them credit).  If you use the words of another author verbatim (word-for-word), you must indicate that by putting the words in quotation marks.  As a UC Davis student, you are expected to know when and how to cite and paraphrase correctly.  If you do not, ask me or your TA for help.  Submitting work that contains work "borrowed" from others and not properly cited is called "plagiarism" and is a violation of our Code of Academic Conduct.*

[^1]: See <https://ossja.ucdavis.edu/syllabus-suggestions>

# *Tentative* schedule

- Week 1 (Sept 25)
    + Introduction
    + Preliminary definitions
    + Introduction to Julia
- Week 2 (Sep 30, Oct 2)
    + Static optimization
    + Numerical differentiation and root-finding
- Week 3 (Oct 7 & 9)
    + Solving an infinite horizon, one-sector growth model
    + Numerical methods for optimization
- Week 4 (Oct 14 & 16)
    + Mathematical foundations of deterministic Dynamic Programming (DP)
    + Numerical solutions for DP
- Week 5 (Oct 21 & 23)
    + Mathematical analysis of DP, adding uncertainty
    + Function approximation, numerical integration
- Week 6 (Oct 28 & 30)
    + Examples of DP
    + More numerical DP solution methods
- Week 6 (Nov 4 & 6)
    + Mark out. Guest speakers.
- Week 7 (Nov 13)
    + Veteran's Day
    + Introduction to Optimal Control (OC) and ODEs
    + Numerical integration with finite difference methods
- Week 8 (Nov 18 & 20)
    + The Maximum Principle, autonomous problems, phase diagrams, stability
    + Shooting methods
- Week 9 (Nov 25 & 27)
    + Constrained OC, transversality conditions, infinite horizon, discontinuities
    + Projection methods
- Week 10 (Dec 2 & 4)
    + Taking dynamic models to data: Euler equations, SMM, dynamic discrete choices

# *Tentative* course objectives

By the end of this course, my goal is that you are equipped to do the following things. This is a ***very*** ambitious list, so *I expect that we will not get to all of these topics!* (No need to panic!)

- Static Optimization
    + Characterize the minimum or maximum of a continuously differentiable nonlinear function. This includes understanding whether the optimum is local or global, and whether constraint qualification may fail. Discuss the geometric interpretation of the Lagrange formulation of the problem
    + Identify and use multiple optimization algorithms that may be suited for a particular problem. Be able to distinguish when the problem requires linear or nonlinear; local or global; constrained or unconstrained; zero, first, or second-order methods. Solve for the maximum of a constrained problem, a likelihood of a nonlinear model, and a variety of other economic problems.

- Numerical methods
    + Compute and check numerical gradients. Understand the idea behind automatic differentiation and when using a software implementation of automatic differentiation may be useful.
    + Compute integrals using appropriate quadrature, Monte Carlo, or Quasi-Monte Carlo methods.
    + Approximate a function using finite element or spectral methods (B-Splines and Chebyshev polynomials). Construct an appropriate approximation scheme from scratch for a simple one-dimensional problem, or use a toolbox for a multi-dimensional one. Identify conditions under which one scheme may perform better than another in some problems. Identify other approximation methods such as shape-preserving splines that may be helpful in particular applications.
    + Implement Newton or Broyden's method for root-finding. Understand under what conditions these methods may fail. Write code from scratch to do this in the univariate case, or use a toolbox for the multivariate case.
    + Solve an infinite horizon dynamic program with discrete or continuous states using value function iteration and policy function iteration. Be familiar with other iterative solution methods for dynamic programs and when these may improve solutions
    + Simulate from the equilibrium distribution implied by a dynamic model
    + Be familiar with the mathematical properties behind finite-difference and projection methods for solving differential equations. Use a toolbox to numerically solve an ODE using one of these methods.
    + Compute the optimal path of a continuous, deterministic dynamic problem using both shooting and projection methods and under a variety of transversality conditions. Know how to handle constraints through switching solution regimes.

- Dynamic Optimization
    + Formulate an original dynamic problem in discrete time as a dynamic program (DP) and continuous time as an optimal control (OC) problem. Identify the state space and action space. Identify static versus dynamic payoffs and discuss the role of each in agents' decisions. Identify and interpret the state transition. Argue why either DP or OC is more appropriate for the problem at hand.
    + Formally argue that the solution to the functional equation representation of a dynamic program is equivalent to the sequence problem. Argue for the existence and uniqueness of the solution. Characterize the shape of the value function. Argue for the existence of a unique policy function and characterize its shape. Interpret the economic content of Euler equations
    + Solve for general solutions to linear FODEs and SODEs by hand. Given boundary conditions, solve for particular solutions.
    + Interpret the economic content the Hamiltonian and co-state variables. Convert between current and present value co-states.
    + Characterize the optimal path of a deterministic problem in a dynamic setting using the "cookbook" optimal control approach. Use restrictions on the shape of payoff functions and state transitions to analytically characterize the behavior of the optimal path.
    + Identify transversality conditions and explain the intuition behind how each will shape agents' optimal actions.
    + Use a phase diagram to characterize the family of solutions for an optimal control problem: identify saddle paths, nullclines, long-run equilibria, separatrix, motion (force) vectors
    + Characterize the stability of a long-run equilibrium using the eigenvalues of a linearized system. Formally argue for the uniqueness of the steady-state.

- Structural estimation
    + Know that calibration and estimation approaches to parameterizing single-agent dynamic models exist. Understand that @hansen1982generalized GMM, and SMM, DCDP/MLE are all approaches to estimating these, and articulate which approach might work for a particular application.
    + Know about the NFXP, MPEC, and Hotz-Miller approaches to estimating a single-agent dynamic discrete choice model

# References
