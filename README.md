# Introduction to static monitoring in PAMGuard

## Introduction
This tutorial is a step by step guide for using PAMGuard to process long term recordings from a static autonomous recorder. The tutorial uses example data from a SoundTrap device deployed off the  Scottish West Coast with plenty of dolphin and porpoise encounters. 

## Species
- Dolphins (multiple species)
- NBHF (harbour porpoises)
- Humpback whales
- Sonar

## What you will learn
Users will be guided step by step in how to create a workflow in PAMGuard which processes medium frequency data to find whistles from dolphins and lower frequency data to detect baleen whale calls and man made sounds such military sonar. Some basic soundscape metrics such as a third octave noise measurements and long term spectral averages are explored. The SoundTrap device that was used to record also runs an on-board click detector at high frequencies to detect porpoise and dolphin echolocation clicks. The tutorial demonstrates how to import these data into PAMGuard. 

Once users have set up their workflow the dataset contains a subset of sound files to process as an example. The dataset also contains the entire *processed* dataset so users can open PAMGuard viewer mode and view weeks of data as if they had processed the entire dataset. The tutorial demonstrates how to navigate through and visualise processed data, run additional species classifiers and export data to MATLAB, R and wav files. 

By the end of the tutorial uses will be familiar with the basic capabilities of PAMGuard and how to construct an acoustic workflow and use the processed data. This provides a foundation for using more complex automated analysis methods such as deep learning classifications, click train detector and localisation methods. 

![The data map in PAMGuard visualises the output from different automated detectors across the whole dataset](/datamap_screenshot.png)

_The data map in PAMGuard visualises the output from different automated detectors across the whole dataset. In this tutorial, users will be working with a 3 month dataset recording at 96kHz with a click detector sampling at 576kHz._

## Getting started
The tutorial text is located in the repository (Introduction to PAMGuard.pdf). You will also need to download the accompanying dataset from Zenodo [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13880212.svg)](https://doi.org/10.5281/zenodo.13880212)

Risch, D., Quer, S., Edwards, E., Beck, S., Macaulay, J., Calderan, S. (2018). Acoustic data from the Scottish west coast recorded with a single-element recording unit doi: 10.5281/zenodo.13880212
