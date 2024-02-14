# Data Science Thesis (MSc Information Studies UvA)

In this repository you will find the code used for the my master thesis about the following topic:

This study compares the performance of the hillClimber algorithm to that of the hillClimber with a plugged in Frequency Fitness Assignment (FFA) method on the optimization of 240 Job Shop Scheduling Problem (JSSP) instances. The JSSP instances have been specifically generated for this study in order to investigate the performance of the algorithms on problem instances with steadily increasing numbers of jobs and machines. 

The comparison of the so called FFA-hillClimber and the standard hillClimber is done in two sets of algorithms, one set with an uphill selection setting, meaning that the algorithms only accept new solutions with positive objective function changes, and a set with a sideways selection setting which means that the algorithms also accept neutral changes on their search paths. 

In the results of this study, the FFA-hillClimbers are more successful at outperforming or matching the performance of the regular hillClimbers on smaller problem instances, as expected. It also becomes apparent that the FFA-hillClimber is most beneficial in relation to an algorithm that gets stuck more easily in local optima. Furthermore, the results hint at behavioral patterns based on the ratio between jobs and machines in individual instances for all four algorithms that would be interesting to study in more depth in the future.
