# Bayesian Hitter Projections

This will serve as the home for the aforementioned Bayesian Hitter projections, and overall projection system. We will start with projecting a relatively stable metric like K%, and will move forward from there.

More specifically, this will take the form of a hierarchial Bayesian model for projecting qualified MLB hitter strikeout rate (K%), evaluated out of sample against standard baselines. We will add calibrated uncertainty intervals as a part of the model as well.

![Shrinkage plot](reports/figures/shrinkage.png)

## Summary

- **Question:** Can a hierarchial Bayesian model beat Marcel-style projections for next-season K%, and are these uncertainty intervals honest and useful?
- **Data**: We will use and rely on FanGraphs season-level batting data, starting in 2015 by using `pybaseball`.
- **Method**: We will use a Binomial likelihood with player-level random effects on the logit scale and a shared aging curve, and this will be fit in PyMC.
- **Result**: TBD
- **Takeaway**: TBD 


