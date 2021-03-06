### Table of Contents

  1. [Installation](#installation)
  2. [Project Motivation](#motivation)
  3. [File Description](#files)
  4. [Results](#results)
  5. [Acknowledgements](#acknowledge)
  
## Installation <a name = "installation"></a>

You will need the standard data science libraries found in the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.

## Project Motivation <a name = "motivation"></a>
In this project, I build a few machine learning models to predict how consumers respond to promotions, so that future offers will be sent out effectively. Specifically, I aim to answer these four questions: 

1. Who completes offers and who doesn't? (Logistic Regression, Decision Tree)
2. For people responding to different offers, how do their demographic characteristics differ? (Multiclass Decision Tree)
3. For completed offers, how long does it take for consumers to complete them? (GLM)
4. Who makes purchases without receiving offers? What offers should be sent to them to maximize profits? (Clustering Analysis)


## File Description <a name = "files"></a>

`starbucks_promotions.ipynb` is a notebook of the analysis performed following the CRISP-DM process.

Datasets used for this project can be found [here](https://drive.google.com/drive/folders/11I4soh4EZWUnL4DMnm8dKSF-fU9h-J2e?usp=sharing). 
* portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
* profile.json - demographic data for each customer
* transcript.json - records for transactions, offers received, offers viewed, and offers completed

## Results <a name = "results"></a>

The main findings of the analysis can be found at the [blog post available here](). 

## Acknowledgements <a name = "acknowledge"></a>
  
Thanks to Starbucks for the data.
