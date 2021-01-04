# OWS Challenge

Anomaly detection is a common problem for the most of companies in the world. Its detection must be accurate to not harm any legitimate costumer. The goal here is to analyze a dataset which contains information about credit card usage.

The dataset analyzed here came from several JSON files that contains more than 4.000.000 credit card transactions from 100.000 users. These JSON files were converted into a dataframe which some new features was created, then we transformed that dataframe into a new one with information for each user, like their credit card profile usage, their transaction velocity and some flags, such as suspicious flags based on outliers for some features distribuition.

With the profile of each user, the main goal of this project is not predict whether an user going to fraud or not, but try to learn the their normal behaviour and check for some anomalies.

The pipeline for transform JSON files into a dataframe is described on [estagio_ds_firststeps.ipynb](../blob/main/estagio_ds_firststeps.ipynb) and from this pipeline, the [users_profile.csv](../blob/main/users_profile.csv) is generated to be analysed in [estagio_ds_anomalydetection.ipynb](../blob/main/estagio_ds_anomalydetection.ipynb).
