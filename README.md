java c
Department of Mechanical Engineering
Mechanics and Materials (MCEN30017)
Part 2: Finite Element Analysis (FEA)
Semester 2, 2024
Assignment
Objective:This assignment aims to evaluate students’ ability to use an analytical FEA approach to solve 1D/2D  structural  problems  (see  examples  in  lecture  notes_  and  utilize  both  Matlab  and  a commercial FEA package to give a flavor of conducting research to students and prepare them for structural integrity of a modern world engineering problem.
Assessment:This assignment constitutes 25% of your total grade. You are required to submit an individual report addressing all the questions. The report must be submitted online through the LMS by Friday, October 18, 2024, at 23:59.The report should be at least 15 pages long, including figures, in a word or pdf document format. Alternatively, you may submit a written report of at least  10 to  12  pages, including figures, accompanied by a 4 to 6-minute video presentation (e.g. , a voice-over PowerPoint), explaining your steps for conducting the FEA simulations required for Question 3.
We recommend using an equation editor for writing mathematical equations and formulas. However, you may also use clear and legible handwritten equations if preferred.
Section 1: FEA analytical approach
Question  1.  (20 marks)For the plane truss shown in figure 1, determine the horizontal and vertical displacement of node 1 and node 2, and calculate the stresses on rods A, B, C. Let Young’s modulus E  = 210 Gpa  uniform. cross-section area S  = 4 × 10 −4 m2 for all elements. You should demonstrate:
a)  Calculation of the stiffness matrix for each rod in this figure
b)  Calculation of displacements on nodes 1 and 2 in both horizontal and vertical directions

Figure 1
Question 2.  (20 marks)Most of the engineering problems fall into a category of solution of a partial differential equation (PDE). There are analytical, experimental, and numerical methods to solve these PDEs. Read the following documentation (only the uniaxial tension section) on analytical stress analysis of a circular hole in an infinite plate (you can search for “stress concentrations at holes”).
https://www.fracturemechanics.org/hole.htmlDownload the Matlab code for assignment on LMS , or alternatively go through the following MATLAB help center which guides you through simulation of a circular hole in a rectangular strip.
https://au.mathworks.com/help/pde/ug/stress-concentration-in-plate-with-circular-hole.htmlFollowing the instructions, instead of a rectangle, design a square with a circular hole in the middle of it. Call circular hole diameter “d” and square width “w” and use only fine mesh. We know that the analytical solution is not valid anymore if “d/w”代 写Mechanics and Materials (MCEN30017) Part 2: Finite Element Analysis (FEA) Semester 2, 2024Matlab
代做程序编程语言 parameter is not small enough.
a)  This is the analytical method to the solution of a PDE. Write a maximum of 2 paragraphs on your understanding of the nature of the problem. (4 marks).
b)  Iterate multiple times and report the minimum “d/w” in which maximum stress is three
(3) times higher than the average stress at the edge of the square. Hint: you can find the average stress on one edge  and on the centerline  similar to the way  stress is defined  on the circle  (a few lines of code). (8 marks)
c)  Make a similar geometry in SolidWorks and conduct an FEA analysis. Present both results (8 marks)
Section 2: FEA numerical approach
Question 3  (60 marks)During the tutorial sessions, we have learned how to design and analyze an FEA model. Try to design the model below in SolidWorks and report the required steps to perform. a valid simulation for a prosthetic hip joint replacement. You are supposed to generate the backbone of your model first.  Subsequently,  add  fillets  and  cut-extrudes to the  model to generate the  final  model  as proposed in the next page. Keep the 10 mm bottom edge of the model , and its midpoint as a reference to start your design. Each fillet size is simply written as R5 as an example to convey a 5 mm fillet.
The common practice is to use a dynamic load on the joint; however, we simplify the modeling with a 1500 Newtons of load applied to the spherical part of the joint.
In your report/video presentation:
i)         Show  how  you  construct  your  model   (use  revolve  feature) ,  select  your  material (Titanium alloy- Titanium (Ti-6Al-4V)).   (15 marks)
ii)       Present the boundary conditions that you use to initiate your simulation. In order not to have a rotation in your model, what type of B.C. you would use, and on what edges/faces? Justify your boundary conditions. (10 marks)
iii)      Perform. a mesh sensitivity analysis and demonstrate the regions of high stress on your model, which require further refinement of mesh. Explain your strategy to refine mesh on high stress/ critical zones and report the appropriate mesh size. (10 marks)
iv)      Present   the   regions   of   high  stress  in  your  model   based  on  Von-mises  stress. Demonstrate a graph for the region with the highest stress. Are you able to reduce this stress in your model? (10 marks).
v)        A design engineer has recommended reducing the weight of implant considering a few holes inside the model. Apply a 1 mm fillet for each hole. Develop your model based on the suggested design and conduct a design study to investigate the most appropriate size of the holes in your model. Try holes with a diameter of 6, 8,  10 ,  12 mm.  (15 marks)







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
