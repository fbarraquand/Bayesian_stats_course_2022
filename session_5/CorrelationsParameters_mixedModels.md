## Emerging correlations in the posteriors in mixed models - what to do

Regarding whether one effect should be set to zero in random effects as we do in fixed effects, thoughts are mixed. I tend not to do that, but sometimes you do need additional constraints. 
There is no obvious consensus on what to do but [a recent paper by Ogle and Barber provides some directions](https://esajournals.onlinelibrary.wiley.com/doi/abs/10.1002/eap.2159). Hierarchical centering is definitely an idea whenever possible. In all cases do check that chains converge and do not generate obvious correlations between parameters. We've dissected the Olge and Barber paper [here](https://juliettearchambeau.github.io/BiogecoBayes/Workshop14_EnsuringIdentifiability.html#/). In passing, the first example shows why it is almost always best to center one's covariates.


