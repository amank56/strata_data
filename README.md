# strata_data
A repo of sample data for our PyData Tutorial!

Just clone this repo to get started for our tutorial.

Note: this is a old juypter note book some of attributes are depricated for e.g.
rolling_std(relpace by series)

In the notebook:
#pd.rolling_std(google['LogReturn'], window=window_size) * np.sqrt(window_size)
try replacing:
pd.Series(google['LogReturn']).rolling(window=window_size).mean()

