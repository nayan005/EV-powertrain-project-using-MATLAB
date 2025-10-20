# EV-powertrain-project-using-MATLAB
This paper delves into the design and optimization of powertrains for Gemera with a focus on enhancing efficiency through MATLAB Simulink. Leveraging Simulink's robust simulation environment, engineers can model, analyze, and refine powertrain configurations to achieve greater efficiency.

#MATLAB Code
 m=1988;
rwh=0.5334;
Cd=0.2;
Af=2;
Rho=1.16;
g=9.8;
N=200;
C0=0.009;
C1=1.75*10^-6;
T_fd_IC=1100;
T_fd_EM=600;
load('matlab');
var.time=Sch_Cycle(:,1);
var.signals.values=Sch_Cycle(:,2);
