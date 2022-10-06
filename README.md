![](https://github.com/qiben-jy/NuclearPowerPlantAccidentData/blob/5ad5c50f6b178dd517378fd16b71f91bf9795b3e/LOGO.png)
# Welcome to NPPAD
### NPPAD: a dataset covering various accidents for nuclear power plants

![GitHub](https://img.shields.io/github/languages/count/qiben-jy/NuclearPowerPlantAccidentData)
![GitHub followers](https://img.shields.io/github/followers/qiben-jy?style=social)
![GitHub](https://img.shields.io/github/watchers/qiben-jy/NuclearPowerPlantAccidentData?style=social)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/qiben-jy/NuclearPowerPlantAccidentData)

This repository contains:

1. The background of this project

2. Introduction to the dataset

3. Related data processing scripts

Hopefully, you can use this project to get the needed accident data for nuclear power plants and then develop new accident diagnosis algorithms and benchmarks.

[//]: # (## Table of Contents)

[//]: # (- [Background]&#40;#Background&#41;)

[//]: # (- [Dataset]&#40;#Dataset&#41;)

[//]: # (  - [Workflow overview]&#40;#Workflow overview&#41;)

[//]: # (  - [Dataset structure]&#40;#Dataset structure&#41;)

[//]: # (- [Scripts]&#40;#Scripts&#41;)

[//]: # (  - [Method "mdbtocsv"]&#40;#Method "mdbtocsv"&#41;)

[//]: # (  - [Method "generate_dataset"]&#40;#Method "generate_dataset"&#41;)

[//]: # (  - [Method "show_parameters"]&#40;#Method "show_parameters"&#41;)

[//]: # (- [Maintainers]&#40;#Maintainers&#41;)

[//]: # (- [Contributing]&#40;#Contributing&#41;)

[//]: # (- [License]&#40;#License&#41;)

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#Background">Background</a>
    </li>
    <li>
      <a href="#Introduction to the dataset">Introduction to the dataset</a>
      <ul>
        <li><a href="#Method mdbtocsv">Method mdbtocsv</a></li>
        <li><a href="#Dataset structure">Dataset structure</a></li>
      </ul>
    </li>
    <li><a href="#Related scripts">Related scripts</a>
    <ul>
        <li><a href="#Workflow overview">Workflow overview</a></li>
        <li><a href="#Method generate_dataset">Method generate_dataset</a></li>
        <li><a href="#Method show_parameters">Method show_parameters</a></li>
    </ul>
    </li>
    <li><a href="#Maintainers">Maintainers</a></li>
    <li><a href="#Contributing">Contributing</a></li>
    <li><a href="#License">License</a></li>
  </ol>
</details>

## Background
Nuclear energy plays an important role in global energy supply, especially as a key low-carbon source of power. Safe operation is critical in the generation of nuclear energy, i.e. in nuclear power plants. Given the significant impact of human-caused errors on three serious nuclear accidents in history, artificial intelligence technologies are increasingly being used to assist plant operators in making decisions. Specifically, artificial intelligence algorithms are used to identify the presence of accidents and their root causes. A continuing challenge is the lack of an open dataset in the nuclear power plant domain to measure the performance of various algorithms. we presents a first-of-its-kind public dataset created with the help of PCTRAN, a pre-developed and widely used simulation software for nuclear power plants. The dataset, NPPAD, basically covers most of the common types of accidents that can occur in pressurized water reactor nuclear power plants. It contains time-series data on the status or actions of various subsystems as well as the accident types and severity information. The dataset also incorporates other simulation data like the amount of radionuclide released, which can help users to conduct research beyond accident diagnosis.

## Introduction to the dataset

### Workflow overview

### Dataset structure

## Related scripts

### Method mdbtocsv

### Method generate_dataset

### Method show_parameters

## Maintainers

## Contributing

## License
