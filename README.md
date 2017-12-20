### **mixnet**
<hr>

Function to extend finite mixture regression models in `flexmix` with variable selection abilities through likelihood regularization with `glmnet`. Main use is for modeling heterogeneous and high-dimensional data. 
This approach finds groups of related observations while selecting and estimating the optimal subset of variables within these groups independently. Regularization is based on the elastic net penalty allowing for L1 (*LASSO*) and L2 (*Ridge*) regularization or a weighted combination (*Elastic Net*). 

The PDF includes an extensive theoretic description and a simulation study to test performance of this modeling approach.
