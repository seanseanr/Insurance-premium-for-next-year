# Insurance-premium-for-next-year
Prediction of insurance premium for next year in T-brain competition: This project has 2 points
that matters. First, feature engineering. Because I know little about the insurance, I just use
basic tech to do the data exploration. There are 2 types of data: numerical and categorical
data. I take data.dtype to group these 2 type of data. About numerical data I take correlation
of every item with next premium and pick out the n largest correlation features by pd.nlargest
functions. the value n is adjusted by me to get a better one. About categorical data I just
count the number of every category value of every feature and plot its relation with the next
premium by pd.plot.scatter. Secondly, the model to train and predict. I use DNN and XGBoost
and light GBM. Comes out that light GBM get better score in the competition.
