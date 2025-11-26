## [LastFM Asia Social Network](https://snap.stanford.edu/data/feather-lastfm-social.html)

A social network of LastFM users which was collected from the public API in March 2020. Nodes are LastFM users from Asian countries and edges are mutual follower relationships between them. The vertex features are extracted based on the artists liked by the users. The task related to the graph is multinomial node classification - one has to predict the location of users. This target feature was derived from the country field for each user

|Dataset|statistics|
| -------- | ------- |
|Directed|No.|
|GTCD*|No.|
|Node features|Yes.|
|Edge features|No.|
|Node labels|Yes. Multi class.|
|Temporal|No.|
|Nodes|7,624|
|Edges|27,806|
|Density|0.001|
|Transitvity|0.179|


## [Cisco Networks](https://snap.stanford.edu/data/cisco-networks.html) 

<table>
<tr><th>Dataset Features</th><th>Descriptive Statistics</th></tr>
<tr><td>
  
|Dataset|statistics|
| -------- | ------- |
|Directed| Yes.|
|GTCD*|Yes.|
|Number of graphs| 22|
|Node features| No.|
|Edge features| Yes.|
|Graph labels| No.|
|Temporal| Yes.|
  
</td><td>

|Stats|	Min|	Max|
| -------- | ------- | -------- | 
|Nodes|	86	|278,739|
|Edges|	155	|2,158,346|

</td></tr> </table>




This dataset was provided by the Cisco Secure Workload group. The dataset contains 22 disjoint graphs representing communications among machines running different distributed applications in various enterprises, collected over multiple days between 2019 and 2022. The dataset also includes ground truth groupings for two graphs. The groupings are useful for evaluating tasks such as clustering hosts based on network communications. Also provided are a README file with a detailed description of the datasets and their format, and Python code for reading the graphs, reporting graph statistics, and reading the ground truth file.





##### * GROUND TRUTH FOR COMMUNITY DETECTION
