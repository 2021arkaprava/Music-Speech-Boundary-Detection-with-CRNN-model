# Music-Speech-Boundary-Detection-with-CRNN-model
Here our task was to separate boundaries between music and speech and detect when such event occurs or stops for a course project.



PreProcessing.ipynb   prepares pre-processing of training data. 
CRNN_model.ipynb    contains the model and training and testing. 


Task-1 is detecting onset and offset of the events and logging them in a CSV file.
Task-2 is labelling the whole audio; if a class is present, then it's 1, else it's 0 at that class tag.

Please refer to the report for details of the work.

Our model performance was:
For Task -1: f_score_eventwise:    0.012383901 
             f_score_segmentwise:  0.276517922

For Task -2: Accuracy: 0.46
             F1 Score: 0.804658
