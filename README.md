# bmi-fhir
Calculating BMI at Age from FHIR Documents Blog Post.  This blog post originally appeared on [Algorex Health](https://blog.algorexhealth.com/).

[![nbviewer](https://img.shields.io/badge/view%20on-nbviewer-brightgreen.svg)](http://nbviewer.jupyter.org/github/AlgorexHealth/bmi-fhir/blob/master/FHIR%20BMI%20Results.ipynb)

This repository contains a Jupyter notebook that demonstrates how to create a population BMI chart from FHIR documents. 

## Set-up

*Clone the repo*

```
git clone https://github.com/AlgorexHealth/bmi-fhir.git
cd bmi-fhir
```

*Initialize a virtual environment and build required libraries*
```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

*Ensure that you have downloaded and unzipped the FHIR files need. They should all be in `data/fhir`*

```
cd data
wget  https://s3.amazonaws.com/algorex-working-data/pediatric-fhir-data/fhir.zip
unzip fhir.zip
```

*Start a notebook and run*
```
jupyter notebook
```

