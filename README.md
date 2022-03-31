## Clasificator expresii faciale
-	S-a  folosit baza de date CK+ pentru antrenare
-	S-au redus  toate emotiile la 2 clase (positive vs negative)
-- Positive – happy,surprise
-- Negative – sad,anger,fear,disgust 
-	S-au extras descriptorii cu ajutorul operatorulul HOG(Histogram of Oriented Gradients) 
-	S-a utilizat SVM (Support Vector Machine) 

## Rezultate
| Const 	   | 0.001	    | 0.001	    |0.001	    |0.01	    |0.01	    |0.01	    |0.1	    |0.1	    |0.1	    |
| :---         |     :---:  |    :---:  |   :---:   |    :---:  |    :---:  |    :---:  |    :---:  |    :---:  |    :---:  |
| Gamma   	   | 1		    | 5		    |10		    |1		    |5		    |10		    |1		    |5		    |1		    |
| Precizie     | 0.9281   	| 0.9281   	|0.9281   	|0.9735   	|0.9735   	|0.9735   	|0.9794   	|0.9794   	|0.9794   	|




