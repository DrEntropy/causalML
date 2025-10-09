## Questions

- How can i better understand difference between level 2 and level 3 interventions? Population vs individual level?

Level 3 is: 
P(Y | do(X=x), W=w) vs P(Y | do(X=x), X=x', W) - I.e. what would have happend if X had been x, given that we know it was x' and W=w.  I.e. counterfactuals.

Another way to see it is to think of a simulation. In the simulation we can run the simulation twice, once with X=x and once with X=x', with the SAME seed and see the difference in Y.   Or we can run the simulator and average over many runs with X=x and X=x' to get the average effect.  The first is level 3, the second is level 2.

Read "casual hierarcy " paper by b

- How do I connect the idea of 'graph surgery' to the idea of d-seperation (as in the back-door criterion)?  Can i do train a model and then do surgery on it and set the values of intervened nodes, and see what happens instead of doign back door>? (McElreath's "full bayes" ?) Maybe this requires a generative model. (See video ("graphical identification with the do-calculus")) . I.e. without a graphical model use do calculus, otherwise use your actual model. Or now i see that the rules of do-calculus involve cutting graphs.

- I guess i am having trouble understanding the relationship between using  these front door/ backdoor/ instrumental variable criteria vs using generative models like SCMs or full PGMs.  ANd further between this and various non-parameteric methods like propensity score matching, difference in differences,  synthetic controls, etc. 

- What is the 'consistency' rule exactly? (oh it is in the book, 8.2.5)

- I get a different answer to the assessment then the answer possibilities.  Not sure where i went wrong.

