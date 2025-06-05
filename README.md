# DL_project_Emotion_Classifier

We perform Facial Emotion Recognition using Deep Learning Technniques with the intrepretation of Gradcam.

Directory structure:
  - results/
  - project_code.ipynb
  - project_report.pdf
  - project_presentation.pdf

You can read both the report and the presentation in where we explain in depth the work we have done.

NOTEBOOK:

  You NEED a Kaggle API key. 
    1. Create an account
    2. Go to settings
    3. Scroll down to API
    4. Create New Token
  
  Then you must upload that file into the notebook when you execute first block.
  
  In order to use our pretrained weights you need to downloaded from the given link in "results/Pretrained Weights Link".
  Add these weights into results folder.
  
  Execute the code linearly. Read the commented code and follow the instructions given there.
  
  TIPS:
    1. If you only want to test model, skip training block and go to the next one (remember to download weights)
    2. In order to run GRAD-CAM you need to modify CustomVGG19 as instructed or run the last block in the notebook.
