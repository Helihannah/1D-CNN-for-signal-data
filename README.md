# 1D-CNN-for-signal-data

In this whole project, the goal is to do binary classifications using 1D CNN. The first step is to construct dataloader and datasets for our sginals and labels. After having them, we define the model we expect, then train and test it. During this process, we plot ROC curve and get the AUC to see how well it performs. Finally, we obtain and vasualize output labels and features maps to have a look at what we got.

The key part is to make a proper model whose performance is good. In order to achieve this, we need to adjust all these hyperparameters to make the AUC > 95%. However, my model dose not achieve it, even though I tried to change batch size, convolutionals layers, activation functions and learning rate several times. The highest AUC is still 92.8%. It seems like these hyperparameters donot have an affect on AUC. I suppoose this is because ES and NS signals are very easy to classify, so no matter what parameters we have, the model have similar performance.

In sum, the output of the model is quite good and is what we expect. Feature maps are also clear to see how signals are changing during passing through this network. However, I still do not very understand how to make my model provide the AUC>95%.
