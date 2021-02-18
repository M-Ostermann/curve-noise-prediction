# curve-noise-prediction
Welcome to my github page!  
  
The model objects are created with R for further scientific application of my developed model for curve noise prediction.  
  
They were part of my PhD thesis "Noise prediction of trains in curves" at TU Wien. The thesis is available in the TU Wien library.  
  
The model objects contain:  
-) TempRailRFReg.RDS: random forest model for rail temperature prediction  
-) BroadFDAClass.RDS: FDA model for flanging noise occurrence prediction  
-) TonalLowNNetClass.RDS: neural network model for squeal noise occurrence prediction  
-) TonalHighNNetClass.RDS: neural network model for HF squeal noise occurrence prediction  
-) LevelPCA.RDS: PCA model for including track decay rates (TDR) and rail roughness (RR) measurements into the model(*)  
-) LevelRFReg.RDS: random forest model for prediction of equivalent continuous noise level prediction of one train pass by  
-) LevelRFRegWithoutEnv.RDS: random forest model for prediction of equivalent continuous noise level prediction of one train pass by without using environmental predictors  
  
(*) watch out for the correct order of input data:  
start with RR of the outer rail (OR) from 25 cm to 0.25 cm, afterwards RR of the inner rail (IR) from 25 cm to 0.25 cm, vertical TDR OR from 100 Hz to 5000 Hz, vertical TDR IR from 100 Hz to 5000 Hz, lateral TDR OR from 100 Hz to 5000 Hz and lateral TDR IR from 100 Hz to 5000 Hz  
  
The publication of the model obejcts targets solely scientific research. Any commercial use is prohibited and violate the copyright of the owner.  
  
© Michael Ostermann  
michael.ostermann@tuwien.ac.at
