# data_availability
This repository will be used to store result data from researches in order to make it accessible to anyone who wants to check the validity of the conclusions.

Each branch will contain the data of one single research in order to make different researches harshly separated from one another.

This branch (computer_learning_human_development) contains the results obtained in researches made in 2021 that support the article "A computer learning model inspired by human development".

The files provided are listed below, as well as their contents:
- complete_output_test_images.pkl: A pickled pandas DataFrame with the images used in the training proccess;
- complete_output_test_results.pkl: A pickled pandas DataFrame with the the expected and predicted values for every image in both stages. The indeces for these two pickles are matched;
- stage_I.zip and stage_II.zip: The trained weights for both stages.
