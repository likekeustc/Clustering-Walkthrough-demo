octave:3> Optimization
Loading and Visualizing Data ...
Training set has 208 records.
Cross Validation set has 69 records.
Testing set has 70 records.

 First 10 records from Training set are: 
 X_train =  0.27, -0.01, -0.11, -1.00  ..., y_test = sitting 
 X_train =  0.28, -0.02, -0.11, -1.00  ..., y_test = laying 
 X_train =  0.28, -0.02, -0.11, -1.00  ..., y_test = standing 
 X_train =  0.28, -0.02, -0.12, -1.00  ..., y_test = standing 
 X_train =  0.27, -0.01, -0.15, -0.38  ..., y_test = walkdown 
 X_train =  0.30,  0.10, -0.25, -0.76  ..., y_test = laying 
 X_train =  0.23, -0.05, -0.11, -0.35  ..., y_test = walkdown 
 X_train =  0.22, -0.07, -0.05, -0.23  ..., y_test = walkdown 
 X_train =  0.27, -0.01, -0.11, -0.99  ..., y_test = sitting 
 X_train =  0.30,  0.03, -0.06, -0.99  ..., y_test = standing 
Program paused. Press enter to continue.

===Train Neural Network===
Iteration     1 | Cost: 2.906201e+00

Training Set Accuracy: 100.000000
J_train =  0.00 

Cross Validation Set Accuracy: 100.000000
J_val =  0.00 

Testing Set Accuracy: 100.000000
J_test =  0.01 

===Learning Cure for Numbers of Training Samples===
Iteration     1 | Cost: 9.910961e-01
Iteration     1 | Cost: 2.678902e+00
Iteration     1 | Cost: 2.817838e+00
Iteration     1 | Cost: 2.751388e+00
Iteration     1 | Cost: 2.796615e+00
Iteration     1 | Cost: 2.820916e+00
Iteration     1 | Cost: 2.760382e+00
Iteration     1 | Cost: 2.679839e+00
Iteration     1 | Cost: 2.673058e+00
Iteration     1 | Cost: 2.891047e+00
Iteration     1 | Cost: 2.750803e+00
Iteration     1 | Cost: 2.850084e+00
Iteration     1 | Cost: 2.732028e+00
Iteration     1 | Cost: 2.799248e+00
Iteration     1 | Cost: 2.719777e+00
Iteration     1 | Cost: 2.724250e+00
Iteration     1 | Cost: 2.819990e+00
Iteration     1 | Cost: 2.711807e+00
Iteration     1 | Cost: 2.814201e+00
Iteration     1 | Cost: 2.779150e+00
Iteration     1 | Cost: 2.818271e+00
# Training Examples	Train Error	Cross Validation Error
  	1		NaN	NaN
  	11		3.302658	3.167442
  	21		0.610830	0.880435
  	31		0.386019	0.559651
  	41		1.349341	2.485771
  	51		0.393750	0.720734
  	61		0.055764	0.340080
  	71		0.088501	0.475379
  	81		0.269462	0.235718
  	91		0.206238	0.492272
  	101		0.183043	0.074018
  	111		0.024290	0.000549
  	121		0.259393	0.627615
  	131		0.006771	0.085678
  	141		0.104034	0.136215
  	151		0.074349	0.000025
  	161		0.033376	0.000833
  	171		0.082200	0.000015
  	181		0.018731	0.051580
  	191		0.011566	0.000596
  	201		0.001464	0.002727
Program paused. Press enter to continue.

===Validation for Selecting Lambda===
Iteration     1 | Cost: 2.820498e+00
Iteration     1 | Cost: 2.725222e+00
Iteration     1 | Cost: 2.719782e+00
Iteration     1 | Cost: 2.762967e+00
Iteration     1 | Cost: 2.808022e+00
Iteration     1 | Cost: 2.822509e+00
Iteration     1 | Cost: 2.940880e+00
Iteration     1 | Cost: 2.753961e+00
Iteration     1 | Cost: 2.834974e+00
lambda		Train Error	Validation Error
 0.000000	0.000000	0.056617
 0.000100	0.000068	0.000118
 0.000300	0.000427	0.000471
 0.001000	0.017110	0.018483
 0.003000	0.001613	0.006536
 0.010000	0.008319	0.013775
 0.030000	0.029400	0.064378
 0.100000	0.026348	0.028067
 0.300000	0.070116	0.074577
Program paused. Press enter to continue.

===Validation for Hidden Layer Size===
Iteration     1 | Cost: 3.076300e+00
Iteration     1 | Cost: 2.874504e+00
Iteration     1 | Cost: 2.895938e+00
Iteration     1 | Cost: 2.815773e+00
Iteration     1 | Cost: 2.812438e+00
Iteration     1 | Cost: 2.893165e+00
Iteration     1 | Cost: 2.549404e+00
Iteration     1 | Cost: 2.707333e+00
Hidden Layer Size		Train Error	Validation Error
 2.000000	0.960191	0.996836
 4.000000	0.934096	1.122635
 6.000000	0.001064	0.001026
 8.000000	0.000004	0.000008
 10.000000	0.000124	0.000452
 12.000000	0.000099	0.000158
 14.000000	0.000862	0.004024
 16.000000	0.000004	0.000021
Program paused. Press enter to continue.
octave:4> diary off