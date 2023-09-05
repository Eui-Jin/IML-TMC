# Analysis of Travel Mode Choice in Seoul Using an Interpretable Machine Learning Approach

This code implements the paper, Kim (2021). Analysis of Travel Mode Choice in Seoul Using an Interpretable Machine Learning Approach. Journal of Advanced Transportation. https://doi.org/10.1155/2021/6685004

## Overview

The IML explain the prediction of ML modesl based on a series of post analysis methods. This code contains the implementation of feature interaction, feature importance, and non-linear effects of covariates (accumulated local effects) using R.

## Getting Started

### Dependencies
* R 4.0.3

### Components

#### Dataset
* 'Data' contains sampled travel survey data collected in Seoul metropolitan area in 2016.
* Detailed data descrptions are provided in the [full paper](https://doi.org/10.1155/2021/6685004)

##### IML_ModeChoice.R
* Step-by-step implementation of ML and IML models  is provided in a single file
* Data clearning, modeling, evaluation, and visualization are included
* Refer the IML_ModeChoice.html for a detailed description of the code 


## Notice
* Please refer to the full paper with this code for understanding the logic behind each process

## Authors

[@Eui-Jin Kim](https://sites.google.com/view/euijinkim)


## License

This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgments
* [IML](https://christophm.github.io/interpretable-ml-book/)
