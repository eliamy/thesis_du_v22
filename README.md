# thesis_du_v22
Code for thesis: "Automatic lose gravel condition detection using acoustic observations"
Consists of two main parts. First one for extracting sound features from folders of audio clips. The audio clips are extracted from BORIS even-logging software. In BORIS gravel roads have been tagged accoriding to loose gravel conditions, extracting the files from BORIS makes the assigned tag be a part of the filename. When loading audioclips into python the part of the filename containing the gravel class is kept as to keep of the gravel class of each audioclip

The second part consists of functions to perfrom cross-validation and gridsearch on selected classification models. Here these functions are semi-homemade. A faster more dynamic approach would be to use a pipeline to perform these actions. 
