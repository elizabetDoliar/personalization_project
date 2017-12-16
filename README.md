# Personalization project

Data set: Amazon Grocery and Gourmet Food

Part 1 <br />
Objective: Increase conversion rate from product views to sales. <br />
Comparison of 3 models used for recommender system:
- Baseline model
- Neighborhood-based collaborative filtering (KNN)
- Model-based collaborative filtering with SVD
<br />
Please see part1_submission.ipynb	in folder part I for code to build and train the models
<br />
<br />
<p>Part 2 <br />
Objective: Build our own recommender system. <br />
<p>Recommender system handles sparse and dense data separately:<br />
- For sparse data, we combine:
  - Content-based (build our own)
  - Association rule (build our own)
- For dense data, we combine:
  - Model-based CF
  - KNN
  - Content-based (build our own)
<br />
Please see part2_submission.ipynb	in folder part II for code to build and train the models
<br />
<p>Reference: <br />
- R. He, J. McAuley. Modeling the visual evolution of fashion trends with one-class collaborative filtering. WWW, 2016 <br />
- J. McAuley, C. Targett, J. Shi, A. van den Hengel. Image-based recommendations on styles and substitutes. SIGIR, 2015
