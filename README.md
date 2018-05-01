# REU Student Information 2018

Welcome to the 2018 REU Summer Student Program!

This repository was created to manage the work for the student project: 

**Machine Learning for the Prediction of Solar Flares**

![picture](https://github.com/emailcausey/2018_REU/blob/master/SDO.png)

*Solar Dynamics Observatory*

## Purpose of the Project
Radiation from solar magnetic eruptions has the potential to disrupt telecommunications, power grids, navigation systems, and satellites. These eruptions often originate from active regions in the sun where concentrated areas of highly complex magnetic field configurations suddenly change. Active regions of the sun are currently characterized using the McIntosh classification system manually by experts in the field. This is an arduous and subjective task.

![picture](https://github.com/emailcausey/2018_REU/blob/master/handdrawn_solar_synoptic_map.png)

Given the increase in the amount of satellite data, we believe that the McIntosh classification system and the prediction and characterization of the solar magnetic eruptions may be improved by utilizing this large dataset and machine learning methods.

The proposed REU student summer project will strive to automate the McIntosh classification. The exploration of the the trends seen in the dataset using an ensemble machine learning method will produce results that will be ultimately be integrated into neural network modeling. 

**Overall Objective : Automate the McIntosh-Based Classification System of sunspots using HMI/SDO line of sight magnetograms and statistical machine learning methods.**

## Timeline: TBD

There is a lot to do! Here is a rough idea of what to expect each week.

**Week 1** Orientation. Get computer set up. Begin background reading. 

**Week 2** Finish background reading. Come up with elevator pitch. Finish Objective #1.

**Week 3** Finish Objective #2 and Objective #3.

**Week 4** 

**Week 5**

**Week 6**

**Week 7**

**Week 8**

**Week 9**

**Week 10**

## Literature

The following papers have some key information related to this project:

[McIntosh, P., 1990](https://link.springer.com/article/10.1007%2FBF00158405)

[Colak, T. and Qahwaji,_2007](https://link.springer.com/article/10.1007%2Fs11207-007-9094-3)

[Nishizuka, N. et al., 2017](https://arxiv.org/abs/1611.01791)

## Machine Learning

### What is Machine Learning?

Machine learning is the study of the design and development of computer algorithms that improve automatically through experience. We consider two machine learning approaches to the solar flare prediction problem: an ensemble method and a neural network. 

The ensemble method uses multiple learning algorithms to obtain an improved predictive performance compared with what could be obtained from constituent learning algorithms alone (a combination of weak learners makes a strong learner). Ensemble methods commonly include k-nearest neighbors algorithm, random forest, and support vector machine (SVM). This type of modeling allows the user to become more familiar with the data, gain insight into which features are important, and set a ‘sanity check’ baseline for future complex modeling. Results from this work can be incorporated into neural network modeling. A neural network is an interconnected assembly of rudimentary processing units. The processing ability of the network is stored in the inter-unit connection strengths or weights obtained by a process of adaptation to or learning from a set of training patterns.

### Resources for Machine Learning

The Iris example is a classic way to practice the basics. Here are some links to useful tutorials:

[kNN classification machine learning problem](https://towardsdatascience.com/supervised-learning-with-python-cf2c1ae543c1)

[Random forest classification machine learning problem](https://chrisalbon.com/machine_learning/trees_and_forests/random_forest_classifier_example/)

[SVM](https://www.analyticsvidhya.com/blog/2017/09/understaing-support-vector-machine-example-code/)

[Overview of ensemble methods](https://www.dataquest.io/blog/introduction-to-ensembles/)

### Background Information You Will Need to Know

1. [Basic Information on SDO/HMI](http://hmi.stanford.edu)

- Date launched, predecessors, instruments on board and what they measure, acronyms, what is being measured by HMI

2. What is a magnetogram? Why are they important to classify active regions?

3. [What are HARPs and SHARPs?](http://jsoc.stanford.edu/doc/data/hmi/sharp/sharp.htm)

### Getting set-up with Anaconda and Jupyter Notebook

1. Download the command-line Installer Python 3.6

https://docs.anaconda.com/anaconda/install/mac-os

https://docs.anaconda.com/anaconda/install/verify-install

•	Enter the following command to update all of the packages within Anaconda:
conda update –all

•	Check that everything is there by opening another terminal and typing...

which python

...and then....

which conda

...the location of the paths should appear with each of these commands

2. Install numpy, sciPy, scikit-learn, matplotlib, pandas

conda install numpy
conda install scipy
conda install scikit-learn
conda install matplotlib
conda install pandas

3. [Install Scikit Learn in Python](http://scikit-learn.org/stable/install.html)
4. [Install drms](https://pypi.org/project/drms/)
5. Run the following command from the terminal ...

jupyter notebook

Create a new notebook that you will use to organize your work.

### Objectives

## 1. Find location of McIntosh Classification Information

We need to find the archive data in a form that can easily be downloaded and read by Python code. I have found the following, but all have flaws:

[ARMaps](http://www.solar.ifa.hawaii.edu/ARMaps/)
[solarmonitor](https://solarmonitor.org)
[NOAA](https://www.swpc.noaa.gov/products/solar-region-summary)

## 2. Access SDO/HMI data

We need to access the SHARP data. Useful resources:

Start with Monica Bobra's reference S1

[Bobra: HMI Science Nuggets](http://hmi.stanford.edu/hminuggets/?p=1428)

[Useful tutorial](http://drms.readthedocs.io/en/stable/tutorial.html#basic-usage)

[Specifying date ranges](http://jsoc.stanford.edu/ajax/RecordSetHelp.html)

## 3. Match HARP active regions to NOAA/McIntosh active regions

## 4. 
