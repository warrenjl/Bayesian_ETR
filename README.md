# Bayesian_ETR

Overview:

The provided code simulates data from a quadratic disease progression model, fits our newly developed hierarchical Bayesian change points model to the data, and organizes the collected posterior samples for the purposes of making posterior inference on the unknown model parameters. 

System requirements:
- A standard computer that can install R statistical software and the R package “rjags”
  -	An Intel-compatible platform running Windows 10 /8.1/8 /7 /Vista /XP /2000 Windows Server 2019 /2016 /2012 /2008 /2003
  -	At least 256 MB of RAM, a mouse, and enough disk space for recovered files, image files, etc.
  -	The administrative privileges are required to install and run R‑Studio utilities.
  -	A network connection for data recovering over network.
- The R code has been tested on R 3.6.2

Installation guide:
- Install R at https://www.r-project.org/
- Install R package “rjags” at https://cran.r-project.org/web/packages/rjags/index.html
- Optional: Install R studio at https://www.rstudio.com/products/rstudio/
- Typical install time on a "normal" desktop computer: 30 minutes

Demo:
- [1]-Data_Simulation.txt:  This R statistical software code simulates data from a quadratic disease progression model where each patient has ten equally spaced visits and their own intercept and change point parameters. 
- [2]-Statistical_Method.txt: This R statistical software code fits the newly developed statistical method to the data and collects posterior samples from all model parameters. The deviance information criterion (DIC) for model comparisons is also computed. The R package “rjags” must be installed for this program to run.
- [3]-Posterior_Inference.txt:  This R statistical software code organizes the posterior samples and compares posterior mean estimates for the intercept and change point parameters with the true values used to simulate the data.
- Instructions to run code on data: Copy all three .txt documents into an R script and run the code.
- Expected output: Posterior samples from all model parameters and the DIC.
- Expected run time for the demo on a "normal" desktop computer: 5 minutes

Instructions for use:
- Import data (in similar format to the simulated data in [1]-Data_Simulation.txt) to an R script.
- Copy R code in text document [2]-Statistical_Method.txt and [3]-Posterior_Inference.txt into an R script.
- Run the combined R code.
