# Overview

This page describes and links to a dataset of 30 patients tested for bacterial vaginosis (BV). For each patient, we provide slide images of vaginal microbiota that have corresponding labels of clue cell status as determined by a physician alongside Amsel criteria test values and the patient's diagnosis.

# Cite the Paper

Utilize the following citation if using this dataset:

> Highland and Zhou, Amsel criteria based computer vision for diagnosing bacterial vaginosis, Elsevier Smart Health 2024, https://doi.org/10.1016/j.smhl.2024.100501 

# Data Collection

The data was collected by a physician at Catawba Women's Center in Hickory, North Carolina between August 2022 and February 2023. The physician targeted non-pregnant female patients who self-reported vaginal discharge but did not attempt self-treatment prior to assessment. After agreement to participate in the study, a few samples of the patient's discharge were collected to perform the Amsel criteria and to send out to an outside laboratory for a NuSwab test. Data was collected from 30 patients.

The 30 patients were 20-62 year olds belonging to four racial groups: white/non-Hispanic (15 patients), white/Hispanic (4 patients), African American (9), and Asian (2 patients). According to the NuSwab test, 15 patients were BV positive, 12 were BV negative, and 3 had indeterminate test results. This demographic information is summarized in the figure below:

[![Racial Demographics of Dataset](https://github.com/dehighland/BV_Diagnostics/blob/7510a33836b619a7828fc05f1c2957ece9c7fcf1/IMAGES/DataAge.png)](https://dehighland.github.io/BV_Diagnostics/) 

[![Age Demographics of Dataset](https://github.com/dehighland/BV_Diagnostics/blob/7510a33836b619a7828fc05f1c2957ece9c7fcf1/IMAGES/DataRace.png)](https://dehighland.github.io/BV_Diagnostics/)

The epithelial cells of patient discharge samples were imaged with a Swiftcam 18 Megapixel camera attached to a Swift SW380T 40X-2500X at a power of 40x. Across 30 patients, 3,692 cell images were captured. These 3,692 cell images were subsequently cropped into 11,181 sub-images of individual vaginal flora and assigned a binary label of clue cell status by a physician.

pH values and Amsel whiff test results were also collected for each patient.
