# diffusion-on-networks
Project at University of Oxford simulating contagion and network diffusion, where the adoption of a microfinance program is the "contagion" and the networks are connections within various small villages in India.

This project is based on The Diffusion of Microfinance and respective data by Banerjee et al. One adjacency matrix and household characteristcs included here, but full article and full data + source found at (DOI: 10.1126/science.1236498)
Looks at the community structure of social networks in Indian villages. Uses homophily via assortativity to try to establish some pattern of program adoption (contagion). Goal is then to devise a strategy to choose "leaders" within each village to maximize adoption rates. Strategy is simualted as a model of diffusion on the networks.

Project done as part of the class C5.10 Mathematics and Data Science for Development with Dr. Neave O'Clery

processing and plot - imports data and converts to igraph objects for analysis and computations. does plotting for visualization

diffusion - function to run diffusion model and function to calculate diffusion centrality

variationinfo - calculates variation of information after rewiring and plots to check for robustness of communities

document - written report. first page is a policy brief and rest is an article in PNAS format

Completed March 27th 2019
