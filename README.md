# NEUROBOT

This project aims to make a robot that works on commands received from brain. In other words, it can be controlled by mere thoughts. The following repo tells about the building of the software part of the robot.

## Workdone 
Biological part is done.

Due to problems (mentioned at last) we are unable to move ahead.

## Motivation
To get tasks done, just by using brain thoughts rather than doing them physically. Especially when one is fatigued or medically incapacitated, it will add up as a helping hand. This will be basically mind reading! This can be used for industrial purposes as well. It will serve as a breakthrough in the technological world.

## Introduction

Our ITSP Project (Project is not completed so tagging as a self project) is based on tracking brain signals, manipulating them so that they could be used to simulate and control a robot. The basic motivation behind this project was to help the paralysed people so that they can perform their tasks with the help of the bot , thereby giving them a sense that they themselves are performing those actions. So what we concluded from our brain study is that all the functions which are performed by humans are the results of control and coordination of brain and other body systems. Brain controls the body movements by sending electrical signals. These electrical signals are specifically called EEG ( Electroencephalography ) signals.

Electroencephalography means writing of the electrical activity of the brain. Electroencephalography records the electrical activity of the brain using electrodes placed on the scalp. Measuring electrical activity from the brain is useful because it reflects how the many different neurons in the brain network communicate with each other via electrical impulses.

If we look more closely at paralysis, patients are not able to perform body movements because the contact between the brain and that specific body part has been disrupted due to some injury, accident or birth defects. If we want to perform an action, the 1st process involved is imagination.. This imagination is also done by the patients but it is not converted into action. The imagination is done in the form of electric signals.They can be detected using a set of electrodes placed on the scalp. The plan is to take these “imagination” signals, interpret them and send them to a robot that can do those actions for you. The EEG signals from the brain are extracted, filtered and digitized so that they can be used by the Bot. The bot would use the signals to perform desired action.

Examples in which same method is used:
 
 - [https://youtu.be/3NRxckSlB9s](https://youtu.be/3NRxckSlB9s)
 - [https://youtu.be/gMqw23ccWLk](https://youtu.be/gMqw23ccWLk)

## Brain Study

Acquired info about various parts of Brain like cerebrum, cerebellum , medulla, parietal lobe etc. and the parts which are responsible for hand movementsWe studied in detail how different lobes of the brain works. Mainly the frontal lobe and parietal lobe contribute towards the movements.Frontal cortex contains motor areas which control voluntary movements of all of our limbs. Also brain study was required to have certain knowledge about which electrode to be placed on which part of the brain.

## Study of electrode source
In measurement of EEG signals the system adapted for placement of electrodes on the scalp is called the 10 - 20 electrode system. This system standardized physical placement and designations of electrodes on the scalp. The head is divided into proportional distances from prominent skull landmarks (nasion, preauricular points, inion) to provide adequate coverage of all regions of the brain. Label 10-20 designates proportional distance in percents between ears and nose where points for electrodes are chosen. Electrode placements are labelled according to adjacent brain areas: F (frontal), C (central), T (temporal), P (posterior), and O (occipital). The letters are accompanied by odd numbers at the left side of the head and with even numbers on the right side. Left and right side is considered by convention from the point of view of a subject. We gathered this information by reading various research papers and reading through some pdf describing the experiments performed on EEG signals.This study of electrodes helped us to understand which electrodes signals represent signals corresponding to hand movement.

## EEG datasets
Encephalographic measurements employ a recording system consisting of - electrodes with conductive media - amplifiers with filters - A/D converter - recording device. We used data set available on kaggle to train our ML programme [https://www.kaggle.com/c/grasp-and-lift-eeg-detection/data](https://www.kaggle.com/c/grasp-and-lift-eeg-detection/data) .

## Technical skills required:
- Machine Learning
- Deep Learning
- PyEEG

## Problems in the Project
Unavailablity of Dataset.

More efficient technology is required to cancel the noise and get approximate correct answer.
