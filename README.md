# XGBoost_Recipe_Generator
ML based Recipe generator that uses RecipeNLG's dataset

I already included the trained models as .pkl files.
So if you wish to run the code with same dataset, then open recipe_generator.ipynb and run the last cell.

XGBoost model is used because of its computation speed. I tried using Random Forest classification, But it took a too long (1 Hour +) to train the model. So I stopped the process and changed to XGBoost model.

Sources:
https://www.aclweb.org/anthology/2020.inlg-1.4.pdf
https://github.com/Glorf/recipenlg
https://recipenlg.cs.put.poznan.pl/
https://www.kaggle.com/datasets/paultimothymooney/recipenlg --> Use this to download the dataset.

Folder Structure:

XGBoost_Recipe_Generator
  |
  |- data/
  | |- recipenlg.csv
  |- label_encoder.pkl
  |- recipe_xgb_model.pkl
  |- vectorizer.pkl
  |- recipe_trainer.ipynb
  |- recipe_generator.ipynb
