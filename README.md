# NMA-Project-HCP-FMRI-Emotions-Task
### Authors: Avisha, Abhinav Singh, Hardik Bhatnagar (euqal contribution)
Poster presented in Neuromatch Conference 2020. This was a group project for Neuromatch Academy's Computational Neuroscience Workshop 2020.

## Shared neural activity patterns between facial expression and shape recognition.

### Abstract
Facial expressions are among the most informative stimuli we perceive: Even a split-second impression of a person's face gives us an estimate of their mood and direction of attention. Existing neurological evidence strongly suggests the existence of machinery dedicated to processing facial expressions in the human brain. We consider an essential shape recognition process gates this facial expression processing machinery. Therefore, here we propose a hypothesis that the facial expression recognition mechanism shares some shape recognition steps in the visual system in the cortical areas. We tested this hypothesis using the fMRI data from the Human Connectome Project of 339 subjects performing an emotion processing task. Similar to the Hariri emotion task paradigm, the subjects matched fearful or angry facial expressions with expressions on the bottom of the screen and also matched geometric shapes like longitudinal and latitudinal ellipses. We separately analysed BOLD activations of the cortical surface regions of the two tasks using Multi-variate pattern analysis. We first selected the top 5% most active brain regions for both the tasks using ANOVA feature selection. These selected features using support vector machines linear kernel classified facial expressions recognition from resting-state with an accuracy of 83%. Similarly, for shape recognition, we got 81% accuracy. Further, the selected areas in ventral stream visual cortex like Posterior Inferior Temporal, Fusiform Face Complex, VMV3 in a ventromedial visual area, which best correlated with object recognition, showed a high correlation with facial expression recognition as well. The other cortical regions involving primary and early visual cortical sectors were also common to both the recognition tasks, but with varying degrees of activation. Thus, these results indicate that facial expression recognition and shape recognition have shared neural activity patterns

### Dataset: HCP fMRI dataset, emotion task
#### Experiment paradigm
Alternate face and shape detection tasks
Each task(face/shape) of 18-sec preceding with a 3-sec cue. Total 21 sec for one task. Each run had 6 tasks 3 for faces and 3 for shapes. 2 runs for one subject. 
#### Data available to us:
1. Timeseries_task: 4D matrix: 339*2*360*176-- num_subjects*runs*voxels*timeframes, 1 timeframe = 0.72 seconds
2. Behavioural data: Median response time and Average accuracy of the response for each type of task, each run, each subject

### References: 
1. https://science.sciencemag.org/content/293/5539/2425.full 
2. https://onlinelibrary.wiley.com/doi/full/10.1002/hbm.24841
3. https://www.researchgate.net/post/What_are_the_best_options_for_MVPA-fMRI_analysis
4. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3389290/
