# novelty_detection
OCSVM &amp; IF

  This project was part of my work that began as what I thought would be a simple classification problem.  I was initially told there was data that is submitted for a report and that this data was either denied or approved.  I would then create a model that would be tested against incoming reports that had been denied.
<br><br>
  I slowly found out that this was not the case.  I would only have one class--the Approved reports.  Once a decision boundary was found, I was then asked to determine what it was that is causing these reports to fall outside of the decision boundary.  I had no success on the latter, however One Class SVM and Isolation Forest were used to create decision boundaries on the data.
<br><br>
  I would like to have used more models such as AutoEncoders, but too much time was spent researching how I could explain feature importance on a One Class Classification (Novelty Detection) problem.
<br><br>
Either way, this project should be a reasonable example for someone to explore the Data Engineering --> Data Science --> Machine Learning pipeline that you may be faced with in the wild.
<br><br>
This project was run on a machine that is not my own, and with private data.  Therefore some of the beautiful plotly charts are missing.. *c'est la vie*..
