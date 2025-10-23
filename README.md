Included in repository...: 

Excel data you can download to see sample parameters or create a path for the .ipynb notebooks.

Multiple colab / python notebooks. 
- "Experimental apparatus" notebook will give the iterative growth process: plots for the gaussian process mean, variance, and acqusition function. It's where I would add sample parameters and measured values for each sample (after inputting seed points).
- "loop through weights" notebook multiplies each weight by a factor from [0, 3]. Then it finds and plots the global optimum for each set of weights.
- "pick scatter points" notebook allows you the pick out growth iterations to plot; compute the sensitivity of the gaussian process surrogate model (through Jacobian singular value decomposition); and plots the gaussian process mean, variance, and acqusition function for each sample growth
---> this notebook gives multiple methods to compute the sensitivity and multiple visualizations

** If you want to recreate plots, download excel files that match the name in the script, and then create a path to the file.
