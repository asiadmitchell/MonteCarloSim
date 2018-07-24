# MonteCarloSim
Implemented a Monte Carlo Simulation in Python to assess significance of chromosomal structures, called radials, observed in Fanconi Anemia cells

We performed a Monte Carlo simulation to determine if our observed chromosome radial frequencies suggest hot and cold spots exists. The Monte Carlo simulation randomizes choice based on a discrete distribution. We performed 300, 500, 1,000 and 2,500 iterations. Here, the discrete distribution was chromosome size, where we assume radial frequencies are proportionate to chromosome size. Next, we computed z-scores for each sample (observed count and those generated from Monte Carlo simulation) then converted the z-score to a p-value. 

Publication: Owen N, Hejna J, Rennie S, Mitchell A, Newell AH, Ziaie N, Moses RE, Olson SB. [Bloom syndrome radials are non-homologous and are suppressed by phosphorylated BLM](https://www.ncbi.nlm.nih.gov/pubmed/25766002). Cytogenetics and Genome Research 2015.
