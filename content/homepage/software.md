---
title: "Software stack"
weight: 9
header_menu_title: "Software stack"
header_menu: true
---

In order to be able to run the notebooks provided for the hackathon and conduct data analysis using the tools for the hackathon, the official global hackathon software stack needs to be installed. To do this, please follow this [link](https://github.com/digital-earths-global-hackathon/tools/tree/um-transform/python_envs) and download the environment.yaml file. Then install the python environment with the following command (note: you need to have conda installed and the base environment activated to do this):

conda env create --name hackathon -f environment.yaml

Activate the environment with:

conda activate hackathon

Instead of hackathon you can also choose any other name for your environment.
