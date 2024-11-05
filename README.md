This project seeks to establish whether there is a correlation between stadium attendance (by percentage, rather than raw numbers) and run expectancy based on 24 base-out states (RE24) in 2020 MLB season games.
RE24 is a baseball statistic that predicts the number of runs that a team is expected to score in one half of an inning, given which bases have runners and the number of outs. As there are 8 possible permutations
of runners on base, and 3 possibilities for the number of outs in each base state, there are 24 total states, hence the "24" in RE24. 

RE24 can be used as a proxy for a team's batting performance while still considering some of the context of the inning. If stadium attendance and RE24 are found to be correlated,
it would corroborate the existence a home field advantage -or an away team disadvantage - which would have significance for several types of stakeholders (managers, bookmakers). 
Additionally, this project analyzes the possibility that home field advantage manifests strictly at a lower level;
the relationship between stadium attendance and high-leverage situations, such as when the bases are loaded with a full count, are subjects of investigation in this project. 


The full version of the findings are provided in the document **Analysis.pdf**. The code for replicating the datasets and visualizations is available in the R Markdown file **Code.Rmd**.
A knitted version of the code is available in **Code_HTML.html**. Lastly, there are three text files and one CSV file which contain the raw data for running the code. 
