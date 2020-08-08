# dialect_detector

This dialect detector predicts which dialect of Spanish a sentence is from. For the moment, it only distinguishes between Mexican Spanish and other varieties.
I trained this model using text data from two sources (childes.talkbank.cmu and radioambulante.org).

To use the dialect detector:
1. Launch the project in Binder (may take several minutes): [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/HannahForsythe/dialect_detector.git/master)
2. Open the jupyter notebook 'dialect_predictor.ipyn' 
3. Run all cells in the "Intro" section.
4. In the section "Type sentence, get dialect," type in a sentence and run the cell to get a prediction. 

To see the code interactively:
1. Launch and open the jupyter project in Binder
(may take several minutes): [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/HannahForsythe/dialect_detector.git/master)
2. Open the jupyter notebook 'capstone.ipyn' 
3. You can either 
  (i) run all cells (this includes the time-consuming process of scraping and cleaning the training data), or 
  (ii) skip to the section "Data wrangling" > "Full dataset" > "Read in full dataset from disk" (this skips data scraping but still includes model fitting), or
  (iii) skip to the section "Feature engineering" > "Read in training data from disk"
