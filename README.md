# Last-fm-Gender-Bias-Analysis
Python Jupyter notebooks to accompany the paper 'Exploring Artist Gender Bias in Music Recommendation' submitted to ImpactRS2020. 

## Dataset Downloads
The following experiments use as a baseline, the following datasets:
* Celma's LFM-360K
* Schedl's LFM-1b

We develop a fuzzymatching based methodology to retrieve artist gender meta-data from a locally configured version of the MusicBrainz database. Code repositories are made openly available at the following link: https://github.com/dshakes90/LFM-1b-MusicBrainz-Gender-Wrangler

For those simply interested in running the experiments in this repo, please unpack and the following datasets into the working dir which this repo was cloned:
https://zenodo.org/record/3964506#.XyExE0FKg5m

## Experiment Structure
For each dataset, LFM-1b & LFM-360K, we produce three notebooks:
* 00-Gender-Dist - Initial pre-processing stages to filter the dataset and remove artists with undef gender
* 01-Experiment-1 - Simulates a 'real world scenario' in which users have extreme preference for male artists.
* 02-Experiment-2 - Simulates an 'upside down world' in which users have extreme preference for female artists. 

## Requirements
Please refer to requirments.txt file for project requirements. 

