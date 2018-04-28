# Lipinski structure evaluation

Lipinski has [published](https://doi.org/10.1016%2FS0169-409X%2800%2900129-0) that 80% of drug available on the market are respecting 4 rules,
[the rules of five](https://en.wikipedia.org/wiki/Lipinski%27s_rule_of_five).

Those 4 rules are:

* No more than 5 hydrogen bond donors (the total number of hydrogens present on an oxygen or nitrogen)
* No more than 10 hydrogen bond acceptors (all nitrogen or oxygen atoms)
* A molecular mass less than 500 daltons
* An octanol-water partition coefficient (log P) not greater than 5

This view will calculate those properties and predict the logP on the flight and allows to filter
the molecules by drawing zones in the parallel coordinates chart.
