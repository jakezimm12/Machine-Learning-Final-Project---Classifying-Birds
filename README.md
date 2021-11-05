# Machine-Learning-Final-Project---Classifying-Birds
Final Project for CIS521: Machine Learning - Classifying Birds Via Various Algorithms. We used pre-trained nets for feature extraction, PCA for dimensionality reduction, and K-Means as well as Gaussian Mixture Modeling for clustering and classification. Read attached paper for more!

In this project, we aim to find the best ways to cluster imagesof 230 bird species[1].  The data for the project is from Kag-gle and consists of images of birds and labels of their species.We implement feature extraction using pre-trained neural net-works such as VGG19 and perform dimensionality reductionusing PCA. We experiment with K-means and GMM cluster-ing on the feature extractions of the images.  We evaluate theperformance of our clustering using 1) measures such as distor-tion and entropy, 2) visualization and inspection of images inthe clusters, and 3) prediction accuracy on unseen images sincewe have access to the true label of the images.  We found thatusing VGG19 is best for feature extractions and using GMMwith  50  clusters  and  a  tied  covariance  best  suits  this  datasetwith  appropriate  trade  off  between  cluster  entropy  and  algo-rithm efficiency.  We discovered that clustering detects manydifferent patterns uncorrelated to the labels of the images andthus performs poorly for prediction tasks, but can be extremelyuseful  for  generalizing  similarities  across  species  of  birds  inbiology.
