# TFY4235_Computational_Physics_exam
The repository complete with code, plots and data.

## Assignment: Vibrations of Fractal Drums
In the folder "Assignment", one can find the relevant .ipynb file with julia code. 
There is a separate folder within with all plots produced for the task.

The notebook is run for one $\ell$ at a time, so to produce results for different $\ell$, one must change it and run the notebook anew.

## Exam:
In the folder "Exam", one can find the relevant .ipynb file with julia code. 
In "short_questions.ipynb", one can find answers to problem 2: Short questions.

The ISING_model.jl file was run to produce results for many different $L$, $p$, $H$, etc. 
It was run from the terminal and produced .csv and .txt files to be handled in notebooks described below.

In the notebook "ISING_model.ipynb" data is analyzed for all problems with $H=0$. 
It also conatins small simulations for visualization, e.g. $p\in[0.02, 0.12, 0.22]$ with $T\in[2.1, 2.3, 2.5]$, one metropolis simulation for each.

In the notebook "ISING_model_with_H.ipynb" data is analyzed for all problems with a non-zero external field $H$. 
It also conatins small simulations for visualization, e.g. $H=0$, $T=2.3$, one metropolis simulation for each.
