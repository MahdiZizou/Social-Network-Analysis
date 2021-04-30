# Social-Network-Analysis
Social Network Analysis Project: Covid-19 diffusion network in Gibraltar

Project description:

This project aims to investigate the extent to which the diffusion models can be fitted to actual data of 
Covid-19 infection and recovery statistics.  
Consider the official statistics on covid-19 infection and recovery provided by official organizations such as 
https://www.worldometers.info/coronavirus. Consider a reasonable time period for a selected country of 
your choice, should be a small country to make the subsequent computational time feasible.  

1. Use a starting date where you consider it to stand for initial state. In the statistics of the country at 
the chosen, calculate the initial Infection I0 as the total number of infection minus the total 
recovery. Use the official corona statistical source to draw a plot showing the temporal variations 
of the number of infections and that of the number of recovery.  

2. We want to carry on the simulation using the SIR epidemic model. Use the implementation 
provided in NDLIB library to perform the calculus. Set the number of nodes of the network equal to 
the total population and a very small probability for Erdos random graph of 0.001. Choose a 
infection probability beta and recovery probability beta of your choice (you may inspire from the 
data trend). Run the EDLIB and plot the temporal variation of the Number of infection and 
recovery over time.  

3. Now we want to use the data of official statistics to tune the probability of infection and recovery 
to find a way to match the variations plotted in 2) with that of 1). Suggest an empirical approach 
where, for instance, you vary incrementally the values of alpha and gamma until you visualize a 
figure infections and recovery count closely match that of official statistics. 

4. Now we want to use the official dataset statistics to estimate the probability of infection and 
recovery. Suggest a simple approach to calculate these attributes using the available historical 
dataset. Then input these values to the SIR model and run the simulation to display the variation of 
the infections and recovery. Discuss the relevance of the SIR model for this purpose. 

5. Now we want to treat the death count provided in the statistics. Consider using the SI model for 
this purpose. Similarly to 1), draw the timely evolution of the number of death.  

6. Next use the implementation provided in EDLIB for the SI model and suggest a simple model to 
generate the simulated model that displays the total number of death.  

7. Suggest an empirical and incremental variation of the infection probability in SI model until the 
death variation is close to the real dataset. Discuss the relevance of such approach and probability 
value.    

8. Consider the SEIRS (Susceptible-Exposed-Infected-Recovered-Susceptible) model described in 
https://github.com/ryansmcgee/seirsplus. Set an initial value of parameters of the model and 
display the temporal evolution of the infection and recovery counts.  

9. Similarly to 3), suggest an empirical and possible an incremental approach to attempt to match the 
infection and recovery counts with that of real dataset. 

10. Similarly to 4), use the official statistics to infer the infection, recovery probabilities and other 
parameters of the model. Then run the model again and display the new graph showing the 
variations of the infections and recovery counts.  

11. Use relevant literature to back your reasoning and finding in previous steps.  
