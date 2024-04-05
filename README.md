
<p align="center"> 
  <img src="image/logo.jpg" alt="Logo.png" width="80px" height="80px">
</p>
<h1 align="center"> Dating Recommendation System With Serendipity </h1>
<h3 align="center"> IN4325 - Information Retrieval </h3>
<h5 align="center"> Research Project - TU Delft</a> (2024) </h5>


<p>A research project which investigates the impact of the addition of serendipity on the quality of recommendations of a collaborative filtering dating recommendation algorithm.</p>

<h2> :floppy_disk: Project Files Description</h2>

<p>This Project contains the following files and folders:</p>
<h4>Executable Files:</h4>
<ul>
  <li><b>dating_recommender_knn.py</b> - Includes all functions required for classification operations.</li>
  <li><b>recommender_evaluation.py</b> - Uses the functions defined in the spam_detector.py file and generates the model.txt file after execution.</li>
  <li><b>dataset</b> - Contains processed dataset with compatibility score between users.</li>
    <li><b>Report</b> - Project report.</li>
</ul>


<h2> :clipboard: Execution Instructions</h2>
<p>To execute this project, the order of execution of the program files is as follows:</p>
<p>1) Data will have to be preprocessed and compatibility scores between users will have to be calculated and stored in compatibility_5k.py</p>

<p>Then, the dating_recommender_knn.py file must be executed, which will execute the recommendation algorithms with and without serendipity and calculate the SRDP score for both.</p>

<p>Finally, the recommender_evaluation.py file must be executed to calculate other metrics like RMSE, Precision, and nDCG.</p>
