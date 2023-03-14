# Patient-Admission-Scheduling-Problem
In 2010, Demeester et al. (2010) defined the patient admission scheduling problem (PASP). In addition, they generated 13 benchmark instances based on hospitals' actual conditions by interviewing patients and made them accessible to other researchers on a website (https://people.cs.kuleuven.be/wim.vancroonenburg/pas/,2010). We checked this website. This website provides the best solutions for benchmark instances and the penalty for violating the considered constraints. However, these solutions have not been updated. Therefore, similar to this website, we decided to publish the updated results on a public repository on GitHub.

In 2019, for the first time in the literature, we developed a new version of the patient admission scheduling problem by considering admission time windows assumption for the patients, that will be called PASP_ATW. Therefore, the benchmark instances defined by Demeester et al. (2010) have been updated by adding each patient's earliest and latest admission time. Here we explain how to update the benchmark instances and the results obtained. We updated benchmark instances as follows:

We assumed that in the first week, all patients should be hospitalized on the desired date. In the second week of planning, the earliest and latest admission dates are obtained by decreasing and increasing one day from the desired admission date. The possibility of two days and three days change in the admission time compared to the desired admission date is considered in the third and fourth weeks. Finally, patients' admission dates can be changed up to 4 days from the fifth week to the end of the planning horizon.

The results of solving benchmark instances are as follows: 
[click here.pdf](https://github.com/MRN36802/Patient-Admission-Scheduling-Problem/files/10972286/click.here.pdf)

As mentioned, the results have been published according to https://people.cs.kuleuven.be/wim.vancroonenburg/pas/. The results showed that, for six out of the 13 benchmark instances, better solutions were generated than the best-known solution reported in the literature. The solution of five instances is optimal, and their solution time using our model has been reduced.

