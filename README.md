# MLProject
## This is an ML project to try and see if an MLP can predict a songs popularity based on Spotify metadata and use a PCA to analyze the correlations and tweak the MLP. <br>
## This project was made using Google Co-Lab so a .py file and a .ipynd file will be included.


This project used multiple different libraries that will need to be installed if you are running this project locally. I found that running Torch for my personal computer was easier on Google Colab. The libraries used are:

* [Torch](https://pytorch.org/) 
* [MatPlotLib](https://matplotlib.org/stable/install/index.html) 
* [SciKit-Learn](https://scikit-learn.org/stable/install.html)
* [Pandas](https://pandas.pydata.org/)
* [Numpy](https://numpy.org/install/)
* [Seaborn](https://seaborn.pydata.org/installing.html)

The MLP model was built using the following components:

* Optimer: [Adam](https://docs.pytorch.org/docs/stable/generated/torch.optim.Adam.html)
* Loss: [CrossEntropyLoss](https://docs.pytorch.org/docs/stable/generated/torch.nn.CrossEntropyLoss.html) (My favorite lol)
* ReLu: [LeakyReLu](https://docs.pytorch.org/docs/stable/generated/torch.nn.LeakyReLU.html)
* [Dropout](https://docs.pytorch.org/docs/stable/generated/torch.nn.Dropout.html)

The most I could test accuracy I could manage was 57%. I imagine popularity is just hard to figure out as it is arbitrary and no play count was included. If anyone finds out how to make this a better using these perameters, please let me know! 😄 
