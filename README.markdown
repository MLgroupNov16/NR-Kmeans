This is a program to implement NR-Kmeans algorithm use Scala in IntelliJ
You can download IntelliJ in https://www.jetbrains.com/idea/ and launch scala to run the program.

This starts the application in  ./src/main/scala/Example.scala, which uses the example dataset provided under './datasets/stickfigures_3subs.dat'.

*Dataset:
The stickfigures_3sub dataset contains 900 datas, each data contains 400 features.  

*program
The algorithm file contains four programs for NR-Kmeans algorithm.
KMeansPlusPlus: Run K-means++ init on the weighted point set data.
NonRedHelpers: Generates a random rotation matrix (most likely a positive definite matrix) of size d
NRKmeans: achieve K-means algorithm

The clustering file contains four programs for measuring the result of NRKmeans
PairCountingF1Measure: measuring the F1 measure of the result
NormalizedMutualInformation:Evaluation of the clsutering performance of models based on the normalized mutual information
MutualInformation: measure the 

The data file contains one program 
DataIO:This function loads the data of the given file into a row-based data matrix

The statistics file contains one program
EmpiricalStatistics:Provides simple stats for partitions like mean and scatter of each partition
 



