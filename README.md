# Default of Credit Card Clients

This is a notebook detailing the implementation on Python of six models to maximize a *Bank Revenue* function and compare it to other standard gain and loss functions. We used information of 30,000 Taiwan's customers produced on October 2005, detailed description of the information we used can be found [on the for Machine Learning Repository of University of California, Irvine](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients). 

We use as a *Bank Revenue* function: $$Revenue = \\alpha* True Negative - (1-\\alpha)*False Negative$$, where $$\\alpha$$ is a parameter that allow us to impose a relative value of a default client against a non-default. Since we doesn't know $\\alpha$ we would train our models with $$\\alpha = \\{1/3, 3/7, 1/2\\}$$.

This notebook has four sections: i) data loading and handling, ii) exploratory data analysis, iii) modelling, iv) conclusions."
