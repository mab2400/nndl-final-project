Mia Bramel
5/13/25

Neural Networks & Deep Learning Final Project Code

##To run the code:
- Upload the Jupyter notebook project_notebook.ipynb to Google Colab
- Ensure you are using a T4 GPU runtime
- Upload the contents of the directory "to_upload_to_colab" directly into the content/ 
  folder in Colab. (For example, /content/superclass_mapping.csv)
- Run the notebook, cell-by-cell.

##Also included:
- best_baseline_model: The weights for the Baseline Model (EfficientNetB4 with dual-classification head)
- best_weighted_model: The weights for the Baseline Model + Class-Weighted Cross-Entropy Loss
- best_weighted_finetuned_model_6h: The weights for the Baseline Model + Class-Weighted Cross-Entropy Loss, 
  fine-tuned from block6h onward.