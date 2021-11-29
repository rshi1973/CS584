# CS584

This project is done for IIT CS584, which is also a challenging competition of Kaggle, "predict future sales". For ease of analysis although slow, all
of the codes have been edited and executed in jupyter notebook. We have several notebooks covering the whole machine learning process, and for the saving
of storage spaces, we only uploaded the latest final version of v30. The notebooks are listed as follows:
- v30_data_processing.ipynb, date cleaning and preprocessing
- v30_feature_engineering.ipynb, feature engineering for this project.
- v30_embedding.ipynb, categorical features embedding using DNN.
- v30_lgb_nr_m1.ipynb, lightgbm model, no ensembling
- v30_lgb_nr_m2.ipynb, lightgbm model, ensembling, with high-loss shop and first sale items modeling
- v30_xgb_nr_em_m1.ipynb, xgboost model, no ensembling
- v30_xgb_nr_m2.ipynb, xgboost model, ensembling, with high-loss shop and first sale items modeling
- v30_stack_model.ipynb, stacking model for lightgbm and xgboost ensemble models.
- v30_weighted_model.ipynb, weighted model for lightgbm and xgboost ensemble models.

The final performace is 0.89346, ranked 1698 in Kaggle's public learer board.
