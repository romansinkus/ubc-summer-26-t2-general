**All (before fitting models):**
* remove the GKs altogether
* drop all NAs
* drop countries
* use just the first position
* convert minutes to hours
* drop shots_on_target

**Before Linear regression:**
* remove the players that did not score
* log transform on response variable
* Alpha = 0.1

**Before Logistic regression:**
* add a scored column
* removing goals
* Alpha = 0.1

**Linear regression after doing algorithmic column selection:**
* TODO

**Logistic regression after doing algorithmic column selection:**
* TODO

**Action items:**
* try step with diff significance level and forward/backward
* discuss which features we want
* rerun models when we have agreed on the input variables

**How to evaluate models**
* Linear regression
  * QQ plot
  * Residual plot

* Logistic Regression
  * Overdispersion parameter
  * Quasibinomial
  * Pearson residual plot