### **mixnet**
<hr>

Function to extend the finite mixture regression model framework in [`flexmix`](https://cran.r-project.org/web/packages/flexmix/index.html) with variable selection abilities through likelihood regularization with [`glmnet`](https://cran.r-project.org/web/packages/glmnet/index.html). Main use is for modeling heterogeneous and high-dimensional data. 

This extension allows to find groups of related observations with the EM algorithm while continuously selecting and estimating the optimal subset of variables within these groups independently. Regularization is based on the elastic net penalty allowing for L1 (*LASSO*) and L2 (*Ridge*) regularization or a weighted combination (*Elastic Net*). 
