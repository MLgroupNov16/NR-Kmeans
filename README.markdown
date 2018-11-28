<p>This is a program to implement NR-Kmeans algorithm use Scala in IntelliJ</p>
<p>You can download IntelliJ in https://www.jetbrains.com/idea/ and launch scala to run the program.</p>

<p>This starts the application in  ./src/main/scala/Example.scala, which uses the example dataset provided under './datasets/stickfigures_3subs.dat'.</p>

<p>Dataset:
<p>The stickfigures_3sub dataset contains 900 datas, each data contains 400 features. </p> 

<p>program</p>
<p>The algorithm file contains four programs for NR-Kmeans algorithm.</p>
<p>KMeansPlusPlus: Run K-means++ init on the weighted point set data.</p>
<p>NonRedHelpers: Generates a random rotation matrix (most likely a positive definite matrix) of size d</p>
<p>NRKmeans: achieve K-means algorithm</p>

<p>The clustering file contains four programs for measuring the result of NRKmeans</p>
<p>PairCountingF1Measure: measuring the F1 measure of the result</p>
<p>NormalizedMutualInformation:Evaluation of the clsutering performance of models based on the normalized mutual information</p>
<p>MutualInformation: measure the mutual information</p>

<p>The data file contains one program </p>
<p>DataIO:This function loads the data of the given file into a row-based data matrix </p>

<p>The statistics file contains one program</p>
<p>EmpiricalStatistics:Provides simple stats for partitions like mean and scatter of each partition</p>
 



