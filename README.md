### Table of Contents

  1. [Installation](#installation)
  2. [Project Motivation](#motivation)
  3. [File Description](#files)
  4. [Results](#results)
  5. [Acknowledgements](#acknowledge)
  
## Installation <a name = "installation"></a>

You will need the standard data science libraries found in the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.

## Project Motivation <a name = "motivation"></a>
In this project, I build a few machine learning models to predict how consumers respond to promotions, so that future offers will be sent out effectively. Specifically, I aim to answer these five questions: 

1. Who responds to promotional offers including all types?
2. For people responding to different offers, how do their demographic characteristics differ?
3. If a person responds to an offer, how long does it take for him/her to complete the offer? How does this period differ for differnt offers?
4. If a person responds to an offer, how much would he/she spend based on demographics and offer type?
5. For people who make purchases without receiving promotions, what types of offers should be sent to them?


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
