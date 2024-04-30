## Background

Epilepsy, also known as a seizure disorder, is a brain condition that causes recurring seizures. It is the fourth most common neurological disorder in the world. About 5 million people are diagnosed with epilepsy each year, and currently, there are 3.4 million, or 1.2%, people with epilepsy nationwide. In some people, the cause can be identified. In others, the cause is not known.

Epilepsy can affect people of all genders, races, ethnic backgrounds and ages, and can affect one's safety, relationships, work, and driving. It’s crucial to recognize the patterns and situations when seizures are more likely to occur.  

An electroencephalogram or an EEG is a test that assists in measuring electrical activity in the brain using small, metal discs called electrodes which are attached to the scalp. Brain cells communicate via electrical impulses through neurons. 

These impulses are active all the time, even when we are sleeping. This activity shows up as wavy lines on an EEG recording. Given below is a sample EEG report which depicts brain electric impulses.

## Objective

The objective of this project is to use EEG data collected by the Universitätsklinikum Bonn to classify whether a patient is having a seizure or not.

## Dataset

The Universitätsklinikum Bonn collected EEG data in 5 files, with each file containing EEG datapoints for 100 individuals, each datapoint being the value of the EEG recording at a different point in time. The time for the EEG recording was 23.5 seconds. 

The dataset for this project was gathered from Kaggle, which combined and preprocessed the original dataset, therefore the dataset now consists of 500 patients and 4097 EEG datapoints. For simplicity, these 4097 datapoints were further broken into 23 chunks and we now have 178 datapoints for every 1 second.

Given below are the five possible values of the category column, also called as column ’y’. Value 1 means active seizure activity, whereas 2-5 means no seizure detected.

