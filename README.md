# Experiments
This repository is used to show the experiments built using [TDM](https://github.com/AnnabelleGillet/TDM), that illustrate different capabilities of the library.

## [Comparison with Spark](https://github.com/AnnabelleGillet/TDM-experiments/tree/master/SparkComparison)
In this experiment, we compare the execution time of TDM operators to those of Spark without the added TDM layer, in order to see if TDM induce an overhead compared to the native execution of Spark.

The result of the experiment shows that TDM does not induce an overhead.

## [Examples of analysis](https://github.com/AnnabelleGillet/TDM-experiments/tree/master/Analysis)
Some notebooks are available to show some use cases of TDM.

### Use of the CANONICAL/POLYADIC decomposition
The CP decomposition is used for community detection on a dataset containing the interactions between students of a primary school. You can find de dataset [here](http://www.sociopatterns.org/datasets/primary-school-temporal-network-data/) and a preview of the results [here](https://raw.githack.com/AnnabelleGillet/TDM-experiments/master/Analysis/PrimarySchoolTDM.html).

It is also used for anomaly detection on the DARPA1998 dataset containing a network traffic over seven weeks. The dataset used is available [here](https://datalab.snu.ac.kr/bigtensor/mit_darpa.php) and a preview of the results [here](https://raw.githack.com/AnnabelleGillet/TDM-experiments/master/Analysis/DARPA1998.html).
