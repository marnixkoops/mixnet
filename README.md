# mixnet

Function to extend finite mixture regression modeling through `flexmix` with variable selection abilities by likelihood regularization with `glmnet`. Main use is for heterogeneous and high-dimensional data. This approach finds groups of related observations while selecting the optimal subset of variables within these groups independently. Regularization is based on the elastic net penalty allowing for L1 (*LASSO*) and L2 (*Ridge*) regularization or a weighted combination (*Elastic Net*). 
